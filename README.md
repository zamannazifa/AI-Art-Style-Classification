# AI Art Style Classification

## Overview

AI Art Style Classification is a deep learning image classification project developed for the Artificial Intelligence Methods module.
The project focuses on classifying major art styles based on their visual characteristics using Python, Google Colab, TensorFlow/Keras, and MobileNetV2.

The model was trained to identify artwork images from three art style categories: Cubism, Impressionism, and Surrealism.

## Project Objective
The objective of this project is to apply artificial intelligence and deep learning techniques to analyze artwork images and classify them according to their art style.
The project demonstrates image preprocessing, transfer learning, model training, fine-tuning, prediction, and model evaluation.

## Art Styles Classified
- Cubism
- Impressionism
- Surrealism

## Technologies Used
- Python
- Google Colab
- TensorFlow
- Keras
- MobileNetV2
- NumPy
- Matplotlib
- scikit-learn
- PIL
- Deep Learning
- Image Classification

## Key Features
- Organized artwork images into training and validation datasets
- Preprocessed image data for model training
- Used MobileNetV2 as a transfer learning model
- Trained and fine-tuned the model for improved classification performance
- Generated prediction outputs for artwork images
- Evaluated model performance using training curves and confusion matrix
- Saved trained model files for future use

## Project Structure
AI-Art-Style-Classification/
│
├── AI_Art_Style_Classification.ipynb
├── mobilenetv2_art_styles.h5
├── mobilenetv2_art_styles_finetuned.h5
├── prediction_grid.png
├── training_curves.png
├── training_curves_finetune.png
├── confusion_matrix.png
├── train/
│   ├── Cubism/
│   ├── Impressionism/
│   └── Surrealism/
│
└── val/
    ├── Cubism/
    ├── Impressionism/
    └── Surrealism/

How to Run
1. Open the notebook file in Google Colab:
2. AI_Art_Style_Classification.ipynb
