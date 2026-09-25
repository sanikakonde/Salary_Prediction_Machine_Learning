# Salary Prediction using Machine Learning

This project predicts an employee's salary using machine learning.

The dataset contains information about employees such as age, gender, education, job title, and years of experience.

## Dataset

The dataset is taken from Kaggle:

Kaggle Salary Prediction Dataset-https://www.kaggle.com/datasets/rkiattisak/salaly-prediction-for-beginer

## Features

The main columns used in this project are:

- Age
- Gender
- Education Level
- Job Title
- Years of Experience

The target column is:

- Salary

## What I Did

In this project, I:

- Loaded and explored the dataset
- Cleaned the data
- Performed Exploratory Data Analysis (EDA)
- Handled missing values
- Encoded categorical features
- Scaled numerical features
- Split the data into training and testing sets
- Built a Linear Regression baseline model
- Compared multiple regression models
- Used 5-Fold Cross-Validation
- Used GridSearchCV for hyperparameter tuning
- Evaluated the final model using R², MAE, MSE, and RMSE

## Final Model

After comparing the models and tuning the parameters, Ridge Regression was used as the final model.

### Final Results

- R² Score: 0.8949
- MAE: 10,136.73
- RMSE: 14,090.44

The R² score of 0.8949 means that the model explains about 89.5% of the variation in salary on the test data.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Kaggle Notebook

## Project File

`Salary_Prediction_Machine_Learning.ipynb`

## Conclusion

This project helped me understand the complete machine learning workflow for a regression problem, from data cleaning and EDA to model training, cross-validation, hyperparameter tuning, and final evaluation.
