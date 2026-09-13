# Casestudy2_Machine_learning-
Credit Card Fraud Detection using XGBoost
Overview

This project detects fraudulent credit card transactions using XGBoost on a highly imbalanced dataset.

Techniques Used
SMOTE – handles class imbalance.
XGBoost – trains the fraud detection model.
Threshold Tuning – improves fraud classification.
Feature Importance – identifies important features.
Dataset

creditcard.csv

Class = 0 → Genuine
Class = 1 → Fraud
Workflow
Dataset → Preprocessing → Train/Test Split → SMOTE → XGBoost
→ Threshold Tuning → Evaluation → Feature Importance
Evaluation

The model is evaluated using:

Precision
Recall
F1-Score
Confusion Matrix
ROC-AUC
PR-AUC
Result

The project demonstrates how XGBoost and SMOTE can effectively detect fraudulent transactions despite severe class imbalance.
