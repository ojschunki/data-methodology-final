> for STA5703 Data Mining Methodology Final Project 

# Credit Card Default Classification

This project builds a machine-learning pipeline to predict credit card default using the UCI Credit Card Default Dataset. The notebook includes data preprocessing, model training, and performance evaluation across multiple classical machine-learning models.

## 📌 Project Overview

The goal of this project is to determine whether a customer will default on their next payment based on demographic, payment history, and account-level information. The workflow includes:

- Loading the UCI dataset using ucimlrepo

- Cleaning and preprocessing the data

- Splitting the dataset into training and test sets

- Training several classification models

- Evaluating all models using standard metrics and visualizations

## 📁 Project Structure
```
cc_default_classification.ipynb   # Complete machine learning notebook
README.md                         # Project documentation
```

## 📦 Dependencies

This project uses common Python ML libraries.

To install dependencies:
```
pip install pandas numpy scikit-learn matplotlib seaborn ucimlrepo
```
## 📑 Dataset

UCI Credit Card Default Dataset

30,000 samples

23 predictor variables

Binary target variable:

default_payment_next_month


Dataset loaded via:
```
from ucimlrepo import fetch_ucirepo
```
## 🚀 How to Run

Open the notebook file:
```
cc_default_classification.ipynb
```

Install dependencies (or run `%pip install` commands inside the notebook).

Run all cells sequentially.


## 🧠 Models Included
### 1. Logistic Regression

A linear baseline classifier used to model the probability of default.

### 2. Random Forest Classifier

An ensemble method that uses multiple decision trees to improve prediction robustness.

### 3. K-Nearest Neighbors (KNN)

A distance-based classifier used as a non-parametric baseline.

### 4. Support Vector Machines (SVM)

A classifier that finds the optimal separating hyperplane that maximizes the margin between classes.


## 📘 Results Summary

The notebook concludes with:

- A results table for all models

- ROC comparisons

- Discussion of which model performs best and why


# 📄 License

This project is intended for educational and academic use.
