# Machine Learning Network Analysis

This Jupyter notebook contains a Python script for a machine learning project focused on network intrusion detection. The script uses the NSL-KDD dataset, which is a benchmark dataset for network-based intrusion detection systems (IDS).

## Overview

The script performs the following tasks:

1. **Data Loading and Preprocessing**: The script loads the training and testing datasets, defines the column names, and identifies the indices of nominal (categorical), binary, and numeric features. It also maps attack types to categories and prepares the data for the machine learning model.

2. **Feature Engineering**: The script performs one-hot encoding on the nominal features and standard scaling on the numeric features. It also separates the target variable ('attack_category') from the feature variables.

3. **Model Training and Evaluation**: The script trains a Decision Tree Classifier on the training data and evaluates its performance on the testing data. The performance is evaluated using a confusion matrix and zero-one loss (fraction of misclassifications).

## Dependencies

The script uses the following Python libraries:

- pandas
- numpy
- matplotlib
- sklearn

## Usage

To use this notebook, you need to have Jupyter Notebook installed. You can then clone this repository and run the notebook.

## Results

The script prints the unique attack types in the training and testing datasets, the distribution of attack types and attack categories in the training dataset, and the descriptive statistics of the 'duration' feature after scaling. It also prints the confusion matrix and zero-one loss for the testing data.

## Note

This script is a basic example of a machine learning project for network intrusion detection. For a real-world application, further steps such as hyperparameter tuning, cross-validation, and use of more complex models may be necessary.