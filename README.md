
# Task-4: Logistic Regression

## Objective
Build a binary classification model using Logistic Regression.

## Dataset
Breast Cancer Wisconsin Dataset (from sklearn)

## Steps Performed
1. Loaded dataset using sklearn
2. Split data into training and testing sets
3. Standardized features using StandardScaler
4. Trained Logistic Regression model
5. Made predictions
6. Evaluated model using:
   - Confusion Matrix
   - Precision
   - Recall
   - ROC-AUC
7. Plotted ROC Curve
8. Performed threshold tuning

## Results

After threshold tuning (0.3):

Confusion Matrix:
[[41 2]
 [0 71]]

Precision: 0.97  
Recall: 1.0  

The model achieves perfect recall and very high precision.

## Sigmoid Function

σ(x) = 1 / (1 + e^-x)

This function converts output into probability between 0 and 1.

## Screenshots
