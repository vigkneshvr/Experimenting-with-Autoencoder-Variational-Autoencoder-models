# Experimenting-with-Autoencoder-Variational-Autoencoder-models
I explore a few variations of autoencoders (AE) and variational autoencoders (VAE) for tasks such as image generation and denoising.

**Environment setup**- I use few basic python libraries such as numpy, torch, torchvision, scipy, PIL, matplotlib, torchsummary and other builtin packages such as math for this work. These can installed individually using pip/conda in your local system.

**Details of experiments:**
1) Vanilla autoencoder that can generate new images of handwritten digits that are similar to the images in the MNIST dataset.
   ![image](https://github.com/vigkneshvr/Experimenting-with-Autoencoder-Variational-Autoencoder-models/assets/48051034/aac63ee6-c801-4699-8725-aba2dbafb116)

2) Denoising Convolutional Autoencoder that is capable of generating clear images from noisy inputs.
   ![image](https://github.com/vigkneshvr/Experimenting-with-Autoencoder-Variational-Autoencoder-models/assets/48051034/ac53340c-ae4d-49b9-9659-f1b2f9f29420)

3) Fully Connected Variational Autoencoder (FC-VAE) for generating new images of handwritten digits.
   ![image](https://github.com/vigkneshvr/Experimenting-with-Autoencoder-Variational-Autoencoder-models/assets/48051034/aa8ce456-e26d-4744-8531-ebf9bdbaa21d)


**References:**
[1] https://avandekleut.github.io/vae/
[2] https://github.com/seloufian/Deep-Learning-Computer-Vision/blob/master/eecs498-007/A6/variational_autoencoders.ipynb



