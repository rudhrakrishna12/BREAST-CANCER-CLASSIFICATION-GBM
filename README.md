Gradient Boosting Classification – Breast Cancer Dataset

Project Overview

This project demonstrates Binary Classification using the Breast Cancer dataset from scikit-learn. The goal is to build a robust Gradient Boosting Classifier, evaluate its performance, and save the trained model using pickle for future inference or deployment.

The project is suitable for:

Machine Learning beginners to intermediate learners

Academic mini-projects

Interview and portfolio demonstrations

Dataset Description

Dataset Source: sklearn.datasets.load_breast_cancer

Number of Samples: 569

Number of Features: 30 numerical features

Target Variable:

0 → Malignant

1 → Benign
Project Workflow

Import required libraries

Load Breast Cancer dataset

Convert dataset into Pandas DataFrame

Train-Test Split

Apply Gradient Boosting Classifier

Hyperparameter tuning (good default parameters)

Model Evaluation

Accuracy Score

Classification Report

Confusion Matrix

Save trained model using pickle

Load pickle file and make predictions
Model Performance

Accuracy: ~95–97% (may slightly vary)

Strong precision and recall for both classes
Model Persistence

The trained model is saved as:

gradient_boosting_model.pkl

This allows:

Reuse of the trained model
