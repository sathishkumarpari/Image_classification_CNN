# Image Classification using Convolutional Neural Networks (CNN) - CIFAR-10 Dataset

This repository contains code and resources for training a Convolutional Neural Network (CNN) to classify images from the CIFAR-10 dataset.

## Overview

The project focuses on implementing a CNN to classify images from the CIFAR-10 dataset, which consists of 60,000 32x32 color images in 10 classes. The CNN architecture is designed to achieve high accuracy in image classification tasks.

## Dataset

The CIFAR-10 dataset consists of the following classes:
- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

For more information on the CIFAR-10 dataset, visit [CIFAR-10 Dataset](https://www.cs.toronto.edu/~kriz/cifar.html).

## Dependencies

The following dependencies are required to run the code:
- Python (>=3.6)
- TensorFlow (>=2.0)
- Keras (>=2.0)

Install the necessary packages using pip:

pip install tensorflow keras


Result: 
With CNN, at the end 10 epochs, accuracy was at around <b>70%</b>  which is a significant improvement over ANN.
CNN's are best for image classification and gives superb accuracy. Also computation is much less compared to simple ANN as <b>maxpooling reduces the image dimensions</b> while still preserving the features.
