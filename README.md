# Customer Churn Prediction

A machine learning project that predicts whether a telecom customer is likely to churn based on customer demographics, account information, and subscribed services. The project compares multiple classification models and explores the factors that contribute most to customer churn.

---

## Dataset

- Telco Customer Churn Dataset
- Problem Type: Binary Classification
- Target Variable: Churn

---

## Project Workflow

- Cleaned and preprocessed the dataset by handling missing values and converting data types.
- Performed exploratory data analysis to identify major churn patterns.
- Applied StandardScaler and OneHotEncoder using ColumnTransformer.
- Built and compared Logistic Regression, Decision Tree, and Random Forest models.
- Evaluated models using Accuracy, Precision, Recall, Confusion Matrix, and 5-Fold Cross Validation.
- Improved model performance using threshold tuning and GridSearchCV.

---

## Results

- Logistic Regression achieved the best overall performance on this dataset.
- Random Forest performance improved after hyperparameter tuning but did not outperform Logistic Regression.
- Important churn indicators included tenure, contract type, monthly charges, and tech support.

---

## Tech Stack

- Python
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## Key Concepts Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Leakage Prevention
- Feature Engineering
- StandardScaler
- OneHotEncoder
- ColumnTransformer
- Logistic Regression
- Decision Tree
- Random Forest
- Cross Validation
- GridSearchCV
- Threshold Tuning
- Feature Importance

---

## What I Learned

This project helped me understand the complete machine learning workflow—from preprocessing and exploratory analysis to model evaluation and hyperparameter tuning. It also reinforced the importance of comparing multiple models instead of assuming that a more complex algorithm will always perform better.
