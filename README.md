# Heart Diease Prediction Model - An Analysis of Key Indicators and Metrics

This repository contains the Heart Disease Prediction Model project, which aims to predict the likelihood of heart disease in individuals based on various health parameters and metrics.
The project utilizes machine learning techniques, specifically the XGBoost, Random Forest Classifier, SVM, and Logistic Regression models, to make these predictions.
The dataset used in this project, "Cardiac_data.csv," comprises 294 data points and 14 features, including age, sex, chest pain type (CP), resting blood pressure (trestbps), cholesterol level (chol),
fasting blood sugar (fbs), resting electrocardiographic results (restecg), maximum heart rate achieved (thalach), exercise-induced angina (exang), ST depression induced by exercise relative to rest
(old peak),the slope of the peak exercise ST segment (slope), the number of major vessels colored by fluoroscopy (ca), and thalassemia (thal). 
The target variable is the presence of heart disease (num).
To address the uncertainities of your evaluation metric due to splitting and due to non-deterministic ML methods the were iteratively executed over 10 random states
The project involves hyperparameter tuning of the ML models and employs iterative imputation to handle the nan values in the dataset for the models RandomForest Classifier, SVM,and LogisticRegression.
Based on the model predictivity and results obtained, it shows the best model performance in logistic regression.

The packages versions used in this project - 
Python version - "3.11.4"
numpy - "1.24.4", matplotlib - "3.7.2",sklearn - "1.3.0", 
pandas - "2.0.3",xgboost - "1.7.6", shap - "0.42.1", seaborn - "0.12.2"
