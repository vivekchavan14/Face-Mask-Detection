# Face-Mask-Detection

Dataset link : https://www.kaggle.com/datasets/omkargurav/face-mask-dataset

# Overview

This project aims to detect whether a person is wearing a face mask or not using deep learning techniques with TensorFlow and Keras. It utilizes a custom Convolutional Neural Network (CNN) architecture trained on a dataset consisting of 7553 RGB images labeled as 'with_mask' and 'without_mask'.

# Dataset

The dataset contains 7553 RGB images categorized into two folders:

- with_mask: Contains 3725 images of faces wearing masks.
- without_mask: Includes 3828 images of faces without masks.

 # Model Architecture and Training
 
The model architecture comprises:

- Input layer: (128, 128, 3)
- Convolutional layers with ReLU activation
- MaxPooling layers for down-sampling
- Dropout layers to prevent overfitting
- Dense layers with ReLU activation
- Output layer with 'sigmoid' activation for binary classification
- The model achieved a training accuracy of 94% and a validation accuracy of 96%.

#  To use the model for predictions:

- Provide the path of the image to be predicted.
- The model will analyze the image and predict whether the person is wearing a mask or not.

# Results
The model's performance:

- Training accuracy: 94%
- Validation accuracy: 96%
