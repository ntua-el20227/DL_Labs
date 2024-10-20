
# Deep Learning Lab Exercise 1: Image Classification on CIFAR-10

## I. Project Overview

The goal of this assignment is to develop an **Image Classification** model using variants of the **Wide Residual Networks** architecture. By training a convolutional neural network (CNN) on the CIFAR-10 dataset, the objective is to optimize the model to achieve high accuracy in classifying images.

In this project, we will experiment with different architectural changes and apply advanced **data augmentation** techniques to improve model performance.

## II. Key Tasks

### 1. Architecture Modifications
The project begins with experimenting with various modifications to the architecture of **Wide Residual Networks**. By changing the network’s structure, we will observe how these changes affect the model’s **prediction accuracy**.

### 2. Data Augmentation with MixUp
Once we have identified the architecture that yields the best results, we will implement an advanced data augmentation technique called **MixUp**. This technique generates artificial images by combining training data in a way that better covers the distribution of the classes to be classified. This helps improve the model’s ability to generalize.

## III. Dataset: CIFAR-10

The CIFAR-10 dataset will be used for training and evaluation. It contains:
- **60,000 images** (32x32 pixels, RGB color channels)
- **10 classes** representing: airplanes, cars, birds, cats, deer, dogs, frogs, horses, ships, and trucks.
- Each class contains **6,000 images**.


The task involves classifying images into one of these 10 categories.


## IV. The Model: Wide Residual Networks

### Wide vs Deep Networks
In this exercise, we will explore **Wide Residual Networks** (WRNs), which are a variation of deep convolutional neural networks. While typical deep networks focus on depth (more hidden layers), **WRNs** use fewer layers but more neurons per layer. The goal is to explore how **widening** the network impacts its representation of images and ultimately its performance.

The trade-off between **width** and **depth** in neural networks is an ongoing debate in machine learning research. It has been observed that deeper networks require exponentially more parameters to achieve the same performance as their wider counterparts. Wide Residual Networks, as shown in the paper ["Wide Residual Networks"](https://arxiv.org/abs/1605.07146), demonstrate that increasing the width of ResNets, when done correctly, can lead to better performance and faster training times.

