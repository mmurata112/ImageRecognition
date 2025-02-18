# Sports Image Classification with SVM

This project uses a **Support Vector Machine (SVM)** model to classify sports images into categories such as **Football** and **Golf**. The model utilizes a combination of pixel features and Histogram of Oriented Gradients (HOG) features for classification. Hyperparameter tuning is done using **RandomizedSearchCV** to optimize the SVM parameters.

## Project Overview

The goal is to develop a machine learning model that can classify sports images into predefined categories (Football and Golf). The following steps are involved in this project:

1. **Data Preprocessing**:
   - Images are resized, normalized, and HOG features are extracted.
   - The dataset is split into training, validation, and test sets.

2. **Model Training**:
   - An **SVM classifier** is trained using feature extraction.
   - **RandomizedSearchCV** is used to optimize the hyperparameters (`C`, `gamma`, and `kernel`).

3. **Model Evaluation**:
   - The model’s performance is evaluated using metrics such as **confusion matrix**, **classification report**, and **ROC curve**.

4. **User Interface**:
   - A simple command-line interface allows the user to test images and view the model’s predictions and performance metrics.

## Features

- **Image Classification**: Classifies images into categories like Football or Golf.
- **Prediction with Confidence**: Shows predicted category along with prediction confidence.
- **Model Evaluation**: Displays a confusion matrix, classification report, and ROC curve for model performance.
- **Interactive Menu**: Provides an easy-to-use menu for testing predictions and visualizing evaluation metrics.

## Requirements

To install the required libraries, run the following command:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn scikit-image scipy
