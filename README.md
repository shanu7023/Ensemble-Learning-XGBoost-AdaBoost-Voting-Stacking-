# Ensemble Learning Algorithms using Scikit-Learn & XGBoost

This repository demonstrates the implementation of some of the most popular **Ensemble Learning** algorithms in Machine Learning using **Python**, **Scikit-Learn**, and **XGBoost**.

The project includes implementations for both **Classification** and **Regression** problems.

---

## Algorithms Covered

### 1. AdaBoost Classifier
- Decision Tree Stump as Base Estimator
- Adaptive Boosting
- Accuracy Evaluation
- Classification Report

---

### 2. XGBoost Classifier
- Gradient Boosting using XGBoost
- Configurable Hyperparameters
- Accuracy Evaluation
- Classification Report

---

### 3. Voting Ensemble

#### Voting Classifier
Base Models:
- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree Classifier

#### Voting Regressor
Base Models:
- Linear Regression
- Support Vector Regression (SVR)
- Decision Tree Regressor

Performance Metric:
- R² Score

---

### 4. Stacking Ensemble

#### Stacking Classifier
Base Models:
- Logistic Regression
- Support Vector Machine
- Decision Tree Classifier

Meta Model:
- Logistic Regression

#### Stacking Regressor
Base Models:
- Linear Regression
- Support Vector Regression
- Decision Tree Regressor

Performance Metrics:
- R² Score (Training)
- R² Score (Testing)

---

## Technologies Used

- Python
- NumPy
- Scikit-Learn
- XGBoost

---

## Machine Learning Concepts Demonstrated

- Ensemble Learning
- Boosting
- AdaBoost
- XGBoost
- Voting Ensemble
- Stacking Ensemble
- Classification
- Regression
- Model Evaluation
- Accuracy Score
- Classification Report
- R² Score

---

## Project Structure

```
Ensemble-Learning/
│
├── adaboost.ipynb
├── ensemble_heterogeneous.ipynb
├── xgboost_classification.ipynb
└── README.md
```

---

## Dataset

Synthetic datasets are generated using Scikit-Learn.

### Classification Dataset

- `make_classification()`

### Regression Dataset

- `make_regression()`

No external datasets are required.

---

## Evaluation Metrics

### Classification

- Accuracy Score
- Precision
- Recall
- F1 Score
- Classification Report

### Regression

- R² Score

---

## Learning Objectives

This project helps understand:

- Difference between Bagging and Boosting
- Working of AdaBoost
- Working of XGBoost
- Voting Ensemble
- Hard Voting
- Stacking Ensemble
- Meta Learner
- Ensemble methods for Classification
- Ensemble methods for Regression

---

## Future Improvements

- LightGBM
- CatBoost
- Random Forest
- Gradient Boosting
- Extra Trees
- Hyperparameter Tuning
- Cross Validation
- Feature Importance Visualization
- ROC Curve
- Confusion Matrix
- SHAP Explainability

---

## Author

Developed for learning and practicing Ensemble Machine Learning algorithms using Python and Scikit-Learn.
