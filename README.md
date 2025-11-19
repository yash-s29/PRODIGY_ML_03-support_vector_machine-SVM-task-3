# PRODIGY_ML_03-support_vector_machine-SVM-task-3

Implementing a Support Vector Machine (SVM) classifier to distinguish between images of cats and dogs using the Kaggle dataset. The project focuses on leveraging SVM's capabilities for image classification tasks.

# Cats vs. Dogs Image Classification
# Project Overview

This project aims to classify images of cats and dogs using a Support Vector Machine (SVM) algorithm. The dataset consists of 25,000 training images of cats and dogs, and the model predicts labels for 12,000 test images. The goal is to distinguish between images of cats and dogs with high accuracy.

# Dataset
The dataset used in this project is derived from the Kaggle Cats and Dogs dataset:

-Training Set: 25,000 images of cats and dogs
-Test Set: 12,000 random images of cats and dogs
-https://www.kaggle.com/c/dogs-vs-cats/data

Each image is labeled as follows:

-1: Dog

-0: Cat

# Installation

1.Clone the repository: git clone https://github.com/kusumithasajja/PRODIGY_ML_03.git cd Cats_vs_Dogs_Classification

2.Install the required packages:

pip install -r requirements.txt

# Model Training

The model is trained using a linear SVM with the following steps:

1.Load and preprocess images (resize to 64x64 pixels).

2.Flatten images to create feature vectors.

3.Split the training data into a training set and a validation set.

4.Train the SVM model on the training data.

5.Predict labels for the test images and save the results.

# Performance

The model's performance can be evaluated based on the accuracy of predictions on the test dataset. Further improvements can be made by experimenting with different models or hyperparameters.

# Contributing

Contributions are welcome! Please open an issue or submit a pull request.

# License
This project is licensed under the MIT License.
