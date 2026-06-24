# Pest Classification Model 🐛

## Overview

This repository contains a pest classification system built using deep learning models. The aim is to identify different types of pests from images. It includes model training notebooks, a deployed application, and various model architectures.  

## Table of Contents

- [Motivation](#github.com/sanjanasoori/Pest-Classfication-Model/new/main?filename=README.md#motivation) 
- [Dataset](#dataset)  
- [Models & Architectures](#models--architectures)  
- [How to Run / Demo](#how-to-run--demo)  
- [Results](#results)  
- [Folder Structure](#folder-structure)  
- [Requirements](#requirements)  
- [Future Work](#future-work)  
- [Author](#author)  

## Motivation

- Automate pest detection to help farmers and agricultural professionals quickly identify pest types.  
- Reduce manual effort and errors in pest identification.  
- Potentially improve crop yield and pest management.

## Dataset

- Images of various pests (provide classes if known, e.g. *aphids, beetles, caterpillars,* etc.).  
- Data sources: (mention where dataset came from, e.g. public datasets or your own collected data).  
- Preprocessing: image resizing, normalization, augmentation (rotation, flips, etc.).

## Models & Architectures

This project explores and compares several model architectures, including:

- VGG16  
- ResNet  
- MobileNetV2  
- Xception  
- EfficientNet  

Training is done in TensorFlow / Keras. The model files (e.g. `mobilenetv2_model.keras`) are included.  

## How to Run / Demo

1. **Clone the repository**  
   ```bash
   git clone https://github.com/sanjanasoori/Pest-Classfication-Model.git
   cd Pest-Classfication-Model
2. **Install dependencies**

   ```bash
   pip install -r requirements.txt
3. **Train a model**

   Use any of the provided notebooks (*.ipynb) to train using a specific model architecture.
   Or run the training script:
   ```bash
   python train_tensorflow.py
4 **Run the application**
   python app.py
   This will start a web app (or GUI) where you can upload pest images and get classifications.

## Results

Model comparison (on validation/test dataset) showing metrics like accuracy, precision, recall, and F1-score for different architectures.

## Folder Structure
Pest-Classfication-Model/
│
├── app.py
├── train_tensorflow.py
├── mobilenetv2_model.keras
├── *.ipynb              # Notebooks for different model architectures (VGG16, ResNet, etc.)
├── datasets/            # (if any) raw or processed images
├── requirements.txt
└── README.md

## Requirements

Python 3.x

TensorFlow / Keras

Libraries: numpy, pandas, scikit-learn, matplotlib, opencv

(Recommended) GPU for faster training

## Future Work

Improve model accuracy by adding more data / classes.

Tune hyperparameters, experiment with newer architectures.

Deploy the model as a cloud service (e.g. AWS, Google Cloud, Heroku).

Add user interface enhancements, batch processing of images.

## Author

Sriyaa.S

GitHub: sriyaa-009


---

⚡ This way all your **commands are properly fenced in `bash` code blocks**, folder structure is neatly formatted, and sections look professional.  

Do you also want me to **merge this with your earlier full README (with Overview, Motivation, Dataset, Models, e
