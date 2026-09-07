# Week 4 - Supervised Learning Model Implementation

## Project Overview

This project was developed as part of my Week 4 internship task on supervised learning. The project demonstrates the implementation of a machine learning classification model using Python and the Titanic dataset.

The main objective is to predict whether a passenger survived the Titanic disaster based on passenger-related information.

## Problem Statement

The project aims to predict the survival status of Titanic passengers using supervised machine learning techniques.

The target variable is:

- 0 = Did not survive
- 1 = Survived

## Dataset

The project uses the Titanic dataset, which contains passenger information such as:

- Passenger class
- Gender
- Age
- Number of siblings/spouses
- Number of parents/children
- Fare
- Port of embarkation

## Data Preprocessing

The dataset was prepared by:

1. Checking the dataset structure.
2. Identifying missing values.
3. Handling missing values.
4. Selecting relevant features.
5. Converting categorical variables into numerical values.
6. Performing feature engineering.

## Feature Engineering

Additional features were created, including:

- FamilySize
- IsAlone
- Passenger Title

These features were created to provide additional information to the machine learning model.

## Machine Learning Model

Logistic Regression was implemented as the primary supervised classification model.

The dataset was divided into training and testing sets using an 80:20 ratio.

Feature scaling was performed using StandardScaler before training the Logistic Regression model.

## Model Evaluation

The model was evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- Five-fold Cross-validation

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- GitHub

## Project Files

- `Week_4_Supervised_Learning_Titanic.ipynb` - Complete Python implementation
- `Titanic-Dataset.csv` - Dataset used for the project
- `Week_4_Supervised_Learning_Report.docx` - Detailed project report

## Conclusion

This project demonstrates the complete workflow of a supervised machine learning classification problem, including data preprocessing, feature engineering, model training, validation, evaluation and prediction.
