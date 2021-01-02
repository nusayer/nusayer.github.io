---
layout: project
title: 'Bangla Alphabet Recognition'
date: 07 Jun 2020
image: /assets/images/image6.png
screenshot: /assets/images/image6.png
links:
  - title: GitHub Link
    url: https://github.com/nusayer/bangla-alphabet-recogition
caption: Predicting handwritten bangla alphabet using two-dimensional convolutional neural network
description: >
  Predicting handwritten bangla alphabet using two-dimensional convolutional neural network
# accent_color: '#4fb1ba'
# accent_image:
#   background: 'linear-gradient(to bottom,#193747 0%,#233e4c 30%,#3c929e 50%,#d5d5d4 70%,#cdccc8 100%)'
#   overlay:    true
---

## Data Preprocessing: 
The original dataset had images of varying dimensions. Therefore, all the images were reshaped to 50x50 matrix. 

## Layers Used:
* Two Convolutional ( and max pooling) layers, then two fully connected layers

## Results
* Validation accuracy of _81.70%_ was achieved.

![result](/assets/images/image7.png){:style="float:right; padding:16px"}
Validation Accuracy
{:.figure}

