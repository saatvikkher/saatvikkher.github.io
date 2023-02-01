# Unmasking with GANs

## Description

I want to train a Neural Network, specifically a Generative Adversarial Network (GAN), to remove face-masks from pictures of people. The model will be trained on a dataset of people with and without masks. The result would be an interface that allows you to input a picture of yourself with a mask. The model then reconstructs/predicts the lower-half of your face. The model should work for subjects it hasn't been trained with.

![masks](https://user-images.githubusercontent.com/74080246/215938802-0b08fad6-88dc-4ea7-803e-35ed3c4559d3.gif)

I am to create a dataset of diverse masked and unmasked faces to train and test the model on. The pictures will have the same orientation and the faces will be front-facing. The generated images can be compared to the subject's real faces. It is hard to derive a Loss function to measure the accuracy of the predictions. I will need to figure out how to assess the models performance other than just qualitatively. 

## Goals

- Create a dataset of diverse masked and unmasked, front-facing faces.
- Train a GAN with input = masked faces and output = unmasked faces.
- Evaluate performance on novel faces and trained faces.
