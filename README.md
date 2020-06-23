# Pix2Pix-GAN
The Pix2Pix Generative Adversarial Network, or
GAN, is an approach to training a deep
convolutional neural network for image-to-image
translation tasks like as
● Converting maps to satellite photographs<br>
● Black and white photographs to color<br>
● Sketches of products to product photographs<br>
<h1>How Does it Work ?</h1>
The GAN architecture is comprised of a generator model for outputting
new plausible synthetic images, and a discriminator model that classifies
images as real (from the dataset) or fake (generated). The discriminator
model is updated directly, whereas the generator model is updated via
the discriminator model. As such, the two models are trained
simultaneously in an adversarial process where the generator seeks to
better fool the discriminator and the discriminator seeks to better
identify the counterfeit images.
