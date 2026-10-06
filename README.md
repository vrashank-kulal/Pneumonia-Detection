# Pneumonia Detection from Chest X-Rays

## Project Overview

This project uses deep learning to classify chest X-ray images into two classes:

- NORMAL
- PNEUMONIA

Two deep learning models were trained and compared:

1. Normal CNN
2. EfficientNetB0 Transfer Learning

## Dataset

The project uses a Kaggle chest X-ray dataset containing chest X-ray images for normal and pneumonia classes.

The test dataset contains 624 images.

## Models

### Normal CNN

A convolutional neural network was created from scratch using:

- Convolutional layers
- Max pooling
- Dense layers
- Dropout
- Sigmoid output

### EfficientNetB0

EfficientNetB0 was used as a transfer learning model with ImageNet pretrained weights.

Data augmentation was also used during training.

## Results

| Model | Test Accuracy |
|---|---:|
| Normal CNN | 75.80% |
| EfficientNetB0 | 82.53% |

EfficientNetB0 achieved higher test accuracy in this experiment.

## Sample Prediction

Both models were also tested on a sample chest X-ray image and predicted the image as PNEUMONIA.

## Files

- Colab notebook - Contains the complete training and evaluation code.
- `model_comparison_approach2.png` - Comparison of model test accuracy.
- `confusion_matrices_approach2.png` - Confusion matrices and model classification results.

## Disclaimer

This project is for educational purposes only. The model predictions are not intended for medical diagnosis.
