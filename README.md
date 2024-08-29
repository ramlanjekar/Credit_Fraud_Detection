# Credit Card Fraud Detection Analysis

## Project Overview

This project focuses on analyzing a credit card fraud detection dataset. The primary goals were to address data imbalances, enhance model accuracy, and deploy a neural network to detect fraudulent transactions.

## Features and Techniques

- **Data Investigation**: Analyzed an imbalanced credit card fraud dataset.
- **Data Balancing**: Applied undersampling and SMOTE (Synthetic Minority Over-sampling Technique) to balance the dataset.
- **Visualization**: Utilized advanced visualization techniques to identify and remove outliers, resulting in a 4% boost in model accuracy.
- **Neural Network Deployment**: Trained a neural network model on both the original and the balanced datasets.
- **Model Performance**:
  - Achieved an 85% recall on the oversampled dataset.
  - Achieved a 74% precision on the oversampled dataset.

## Dataset

The dataset used for this analysis is available on Kaggle. You can download it from the following link:

[Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets?search=credit+card+fraud)

## Installation

To replicate this analysis, ensure you have the following Python packages installed:

```bash
pip install numpy pandas scikit-learn imbalanced-learn tensorflow matplotlib seaborn
