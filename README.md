# Supervised-Learning
Breast Cancer Classification using Supervised Learning
### Project Overview

This project applies multiple supervised learning algorithms to the Breast Cancer dataset from sklearn to classify tumors as malignant or benign.

The goal is to compare different machine learning models and evaluate their performance on a real-world medical dataset.

### Dataset
Source: sklearn.datasets.load_breast_cancer()
Samples: 569
Features: 30 numerical features
Target:
0 → Malignant
1 → Benign
### Preprocessing Steps
Missing Value Handling
No missing values were found in the dataset.
Train-Test Split
80% training data
20% testing data
Feature Scaling
Applied StandardScaler
Necessary for:
Logistic Regression
SVM
k-NN
Ensures all features contribute equally
### Models Implemented
1. Logistic Regression
Linear model for binary classification
Uses sigmoid function to predict probabilities
2. Decision Tree Classifier
Tree-based model using feature splits
Easy to interpret but prone to overfitting
3. Random Forest Classifier
Ensemble of decision trees
Reduces overfitting and improves accuracy
4. Support Vector Machine (SVM)
Finds optimal hyperplane for classification
Effective in high-dimensional datasets
5. k-Nearest Neighbors (k-NN)
Instance-based learning
Classifies based on nearest neighbors
### Model Performance
Model	Accuracy
Random Forest	 Best
SVM	High
Logistic Regression	High
k-NN	Moderate
Decision Tree	Lowest

##### Note: Exact accuracy values may vary slightly depending on random state.

### Conclusion
Best Performing Model: Random Forest
Worst Performing Model: Decision Tree

Random Forest performed best due to its ability to reduce overfitting and handle feature interactions effectively.



