# Semantic-Segmentation-using-UNET

This project tries to solve a multi-class semantic segmentation problem using UNET on the [Cityscape Image Pairs](https://www.kaggle.com/dansbecker/cityscapes-image-pairs) dataset. This project implements a variation of the orignal UNET by adding batch normalisation between layers and using same padding. 

## Input
The inputs to the model is an RGB image of a cityscape. 

<p align="center">
    <img width="256" height="256" src="https://github.com/tauseef09/Semantic-Segmentation-using-UNET/blob/master/readme_images/input.jpg">
    <br>
    Sample input
</p>

## Output
The output is a semtantically segmented mask where different objects are color coded.

<p align="center">
    <img width="256" height="256" src="https://github.com/tauseef09/Semantic-Segmentation-using-UNET/blob/master/readme_images/output.jpg">
    <br>
    Sample output
</p>

## Saved Weights
A .pth.tar file can be found [here](https://drive.google.com/drive/u/0/folders/1OroW6nzyOo3882BFTUPFQibFUOxO5kUx) containing weights of this model trained for 100 epochs.

## Authors
This was part of a personal project worked on by: 
- [Tauseef Tajwar](https://github.com/tauseef09)
- [Muftiqur Rahman](https://github.com/Muftiqur1111)

