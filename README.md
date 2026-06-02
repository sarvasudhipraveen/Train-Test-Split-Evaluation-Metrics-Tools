Heart Disease Prediction Using Logistic Regression
Project Overview

This project demonstrates the implementation of Train-Test Split and Evaluation Metrics using the Heart Disease Dataset. The objective is to train a Logistic Regression model and evaluate its performance using Accuracy, Precision, Recall, and Confusion Matrix.

Objectives
Understand Train-Test Split.
Train a Logistic Regression model.
Predict heart disease on test data.
Evaluate model performance.
Interpret evaluation metrics.
Tools & Technologies
Python
Pandas
Scikit-learn
Jupyter Notebook / Google Colab
Dataset

Heart Disease Dataset

The dataset contains patient health information such as age, cholesterol level, blood pressure, chest pain type, and other medical attributes used to predict the presence of heart disease.

Project Workflow
1. Load Dataset

The dataset is loaded using Pandas.

2. Data Preparation
Separate features and target variable.
Define input and output variables.
3. Train-Test Split
80% Training Data
20% Testing Data
4. Model Training

A Logistic Regression model is trained using the training dataset.

5. Prediction

The trained model predicts outcomes for the testing dataset.

6. Model Evaluation

The following metrics are calculated:

Accuracy
Precision
Recall
Confusion Matrix
Evaluation Metrics
Accuracy

Measures overall correctness of predictions.

Precision

Measures how many predicted positive cases are actually positive.

Recall

Measures how many actual positive cases are correctly identified.

Confusion Matrix

Displays:

True Positive (TP)
True Negative (TN)
False Positive (FP)
False Negative (FN)
Results

The Logistic Regression model successfully predicts heart disease and achieves good performance on the testing dataset. Evaluation metrics help measure the effectiveness of the model.
