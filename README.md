# Logistc-Regression-with-ROC-AUC-
Logistic Regression on Imbalanced and Simple Datasets with ROC & AUC

This repository contains two projects demonstrating the implementation of logistic regression on:

* Imbalanced Dataset: A dataset where the class distribution is heavily skewed, which poses challenges for traditional machine learning algorithms. Special techniques are applied to handle this imbalance, and model performance is evaluated using metrics like the ROC curve and AUC score.
Simple Dataset: A more balanced dataset to illustrate the core concepts of logistic regression in a straightforward manner.

Key Highlights:

* Logistic Regression: Implemented using Python’s scikit-learn library.
* Handling Imbalanced Data: Techniques such as class weighting or resampling to deal with skewed class distributions.
  
Performance Evaluation:
* ROC Curve: Receiver Operating Characteristic curve is used to visualize the model's performance.
  
* AUC Score: Area Under the ROC Curve (AUC) is used as a quantitative metric to assess the model's ability to distinguish between classes.
  
Dependencies:
* scikit-learn
  
* matplotlib
  
* numpy
  
* pandas
  
Files Included:
imbalanced_dataset_logistic_regression.ipynb: Notebook implementing logistic regression on an imbalanced dataset.
simple_dataset_logistic_regression.ipynb: Notebook demonstrating logistic regression on a simple, balanced dataset.
roc_auc_analysis.py: Script for ROC curve generation and AUC calculation.
