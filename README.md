# Rock Paper Scissors With Convolutional Neural Networks

## Project Overview

This project demonstrates the implementation of Convolutional Neural Networks (CNNs) using TensorFlow. The goal is to build and train a CNN model to classify images from the Rock-Paper-Scissors dataset. The project covers data loading, preprocessing, model building, data augmentation, training, and interactive predictions.

## Course Information

This project was completed as part of the **"Convolutional Neural Networks with TensorFlow"** course offered on Coursera.
## Key Components

1. **Data Preparation**: 
   - Downloaded and extracted the Rock-Paper-Scissors dataset.
   - Loaded the dataset using TensorFlow's `image_dataset_from_directory` method for training and validation.

2. **Model Architecture**:
   - Constructed a CNN model with multiple convolutional and max-pooling layers.
   - Added a dropout layer for regularization.
   - Used dense layers to classify the images into one of three categories (Rock, Paper, Scissors).

3. **Data Augmentation**:
   - Applied data augmentation techniques such as random flipping, rotation, translation, contrast adjustment, and zooming to improve model generalization.

4. **Training and Evaluation**:
   - Compiled the model with the Adam optimizer and sparse categorical crossentropy loss function.
   - Trained the model for 25 epochs and evaluated its performance using the validation dataset.

5. **Interactive Image Prediction**:
   - Added functionality to upload and classify images using an interactive widget.
   - Displayed predictions for uploaded images with their respective class labels.

## Files

- `Rock-Paper-Scissors-Classifier-With-CNN.ipynb`: Contains the code for building and training the CNN model.
- `data_preprocessing.py`: Includes scripts for downloading, extracting, and loading the dataset.
- `interactive_predict.py`: Provides functionality for interactive image prediction using widgets.
- `README.md`: This file, providing an overview of the project.

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/rezamohamadlo/Rock-Paper-Scissors-Classifier-With-CNN.git
