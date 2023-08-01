# Reverse Image Caption with GANs

**Project Description**

In this project, we explored various GAN architectures, including DCGAN (Deep Convolutional GAN), WGAN (Wasserstein GAN), LSGAN (Least Squares GAN), and SRGAN (Super-Resolution GAN). GANs are a class of deep learning models used for generating new data samples that resemble a given dataset. They consist of a generator network that creates new samples and a discriminator network that tries to distinguish between real and generated samples.

**Project Goals**

1. Implement DCGAN, WGAN, LSGAN, and SRGAN architectures.
2. Fine-tune the GAN models to generate high-quality images.
3. Explore text-to-image translation using the trained GAN models.

**Technologies Used**

The project utilized the following technologies and libraries:

- Python
- Tensorflow
- Numpy
- Matplotlib

**Project Details**

1. **DCGAN (Deep Convolutional GAN):** DCGAN is a popular GAN architecture that uses convolutional layers for both the generator and discriminator networks. We implemented DCGAN and trained it on a dataset of images to generate new, realistic-looking images.

2. **WGAN (Wasserstein GAN):** WGAN is a variant of GAN that introduces the Wasserstein distance as the loss function. It addresses some stability issues faced by traditional GANs. We implemented and fine-tuned WGAN to further improve image quality.

3. **LSGAN (Least Squares GAN):** LSGAN is another GAN variant that uses the least squares loss function instead of the traditional binary cross-entropy. We experimented with LSGAN to generate more visually pleasing images.

4. **SRGAN (Super-Resolution GAN):** SRGAN is a GAN architecture specifically designed for super-resolution tasks, where the goal is to upscale low-resolution images to higher resolutions. We explored SRGAN for text-to-image translation, attempting to generate high-resolution images based on textual descriptions.

**Results and Achievements**

- Successfully implemented and trained DCGAN, WGAN, LSGAN, and SRGAN architectures.
- Generated high-quality images using the trained GAN models.
- Explored text-to-image translation using SRGAN, achieving promising results in generating images from textual descriptions.
