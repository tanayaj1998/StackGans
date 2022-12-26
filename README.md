#Replication of StackGans Paper
In this project I have implemented text to image generation using StackGan.

## Description
This project is my final project for my Deep Learning course. The project consists of implementation of stackGAN model. The model consists of two stages:
stage 1- generates a basic outline of image. It generates a blurred image after 600 epochs.
stage 2- Adds details to the generated image in stage 1. Makes the image have more detail to it.
fist run the stage 1 model. After training it for a certain number of epochs train the stage 2 model for the same number of epochs.

I have used the CUB dataset. Before running the code make sure to add 3 folders to your main directory:
1. test Folder - stores stage 1 images
2. weights Folder - stores weights for models
3. results_stage2 Folder - stores images of stage 2 during training
Get the CUB dataset from here - http://www.vision.caltech.edu/visipedia/CUB-200-2011.html
For text embedding download char-CNN-RNN text embeddings for birds from -
https://drive.google.com/file/d/0B3y_msrWZaXLT1BZdVdycDY5TEE/view?resourcekey=0-sZrhftoEfdvHq6MweAeCjA or https://github.com/hanzhanggit/StackGAN
## Authors

Tanaya Joshi - tj2181
tj2181@nyu.edu

## Acknowledgments

Inspiration, code snippets, etc.
* (https://arxiv.org/abs/1605.05396)
* (https://arxiv.org/abs/1612.03242)
* (https://github.com/hanzhanggit/StackGAN)
* (https://github.com/AarohiSingla/StackGAN)
