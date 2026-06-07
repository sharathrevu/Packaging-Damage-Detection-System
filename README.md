# Packaging-Damage-Detection-System

This project uses Deep Learning and Computer Vision techniques to classify package images as Damaged or Intact. A custom CNN model is developed and compared with a Transfer Learning model (MobileNetV2) to evaluate classification performance.

## Project Overview

The objective of this project is to automate package inspection using image classification. The system learns visual features from package images and predicts whether a package is damaged or intact.

## Features

- Dataset loading and preprocessing
- Image resizing and normalization
- Data augmentation
- Custom CNN model
- MobileNetV2 transfer learning model
- Model training and evaluation
- Confusion matrix
- Classification report
- Accuracy and loss curves
- ROC curve
- Model comparison

## Dataset

The dataset contains images from two categories:

- Damaged Packages
- Intact Packages

Source: Kaggle – Damaged and Intact Packages Dataset

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## How to Run

### 1. Download the Dataset
Download the dataset from Kaggle and place it in the appropriate directory.

### 2. Install Required Libraries

bash pip install tensorflow numpy pandas matplotlib seaborn scikit-learn pillow 

### 3. Open the Notebook

Launch Jupyter Notebook:

bash jupyter notebook 

Then open the uploaded .ipynb file.

### 4. Update Dataset Path

Locate the dataset path variable in the notebook and update it if necessary:

python base_path = "your_dataset_path" 

### 5. Run All Cells

Run the notebook from top to bottom:

text Kernel → Restart & Run All 

### 6. View Results

The notebook will generate:

- Accuracy and Loss Curves
- Confusion Matrix
- Classification Report
- ROC Curve
- Model Comparison Results

Saved figures will be stored in the current working directory.

## Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC Score

## Future Improvements

- Grad-CAM visualization
- Hyperparameter tuning
- Additional transfer learning models
- Web application deployment

## Author

Deep Learning Project – Damaged vs Intact Package Classification
