# 🧠 Mental Health Treatment Prediction using Machine Learning

This project aims to predict whether an individual is likely to seek mental health treatment based on various demographic and workplace-related factors. The dataset used comes from a mental health survey and includes both categorical and numerical features.

## 💡 Project Highlights

- Manual data cleaning and imputation
- Column-wise preprocessing using `ColumnTransformer`
- Feature scaling and encoding in a `Pipeline`
- Model building with Logistic Regression
- Hyperparameter tuning using `GridSearchCV`
- ROC Curve plotting for model evaluation

## 📁 Dataset

The dataset contains features like:
- Age, gender, and country
- Company size and remote work status
- Work-life balance, mental vs physical health perceptions
- History of mental health issues

**Target column**: `treatment` (Yes/No)

## 🧪 Model Evaluation

Models were evaluated using:
- Accuracy
- Precision, Recall, F1-Score
- Confusion Matrix
- ROC-AUC Curve

## 🛠️ Tech Stack

- Python 3.10+
- pandas, numpy
- scikit-learn
- matplotlib, seaborn
