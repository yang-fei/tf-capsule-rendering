Capsule ImageCGAN
======================================================================
Code repo for the ACCV 2018 paper, "
Capsule Based Image Synthesis for Interior Design Effect Rendering", Fei Yang, Zheng Lu, Guoping Qiu, Jing Lin, Qian Zhang.

University of Nottingham Ningbo China

This project builds capsule blocks in image-conditioned GAN (generative adversarial network) to learn the image translation from a plain image into a rendered image. A line preservation loss is implemented not only to constrain the line shapes, but also to improve the light effects around these lines at the same time.


The code will be released after the conference. The project page is under building by F.Yang et al. https://yang-fei.github.io/tf-capsule-rendering.


## Prerequisites
- tensorflow 1.4+
- numpy 
- scipy
- pillow
## Code tested on
The code has been tested to work well with below hardware or software, but should not be limited in belows. 
- Ubuntu 14.04/16.04
- NVIDIA GPU GTX1080/GTX1080TI/GTX TITAN X/TITAN X(PASCAL)
- CUDA 8.0/9.0/9.1
- CuDNN v5.1/6.0/7.1
- tensorflow 1.4/1.6/1.8/1.9

## Getting Started
```sh
# clone this repo:
git clone https://github.com/yang-fei/tf-capsule-rendering.git
cd tf-capsule-rendering
# download the pretrained weights



