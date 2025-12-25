# Iris Flower Species Classification Using Decision Tree
## Project Overview:

This project focuses on building a machine learning classification model to predict the species of an Iris flower — setosa, versicolor, and virginica — using sepal and petal measurements.
It demonstrates a complete end-to-end machine learning workflow including data exploration, preprocessing, model training, and evaluation.

## Problem Statement:

The objective of this project is to develop a machine learning classification model that accurately predicts the species of an Iris flower based on its physical measurements such as sepal length, sepal width, petal length, and petal width.

## Dataset:

- Source: External Iris CSV dataset
- Total records: 150
- Features:
sepal_length, sepal_width, petal_length, petal_width

- Target:
species (Setosa, Versicolor, Virginica)

## Exploratory Data Analysis (EDA):

- Univariate, bivariate, and multivariate analysis was performed.
- Petal-based features were identified as the most influential predictors.
- The dataset was found to be clean, balanced, and free of missing values.

## Preprocessing Steps:

- Encoded categorical target variable
- Separated features and target
- Split data into training and testing sets

## Model Used:

Decision Tree Classifier
- Suitable for non-linear multi-class classification
- Requires no feature scaling
- Easy to interpret

## Model Performance:

- Achieved very high accuracy due to the clean and highly separable nature of the Iris dataset.
- Classification report and confusion matrix were used for evaluation.

## Key Insights:

- Petal length and petal width are the strongest predictors.
- Sepal features have comparatively lower class-separating ability.
- Tree-based models perform extremely well on clean datasets like Iris.

## Conclusion:

This project demonstrates a complete machine learning pipeline from data understanding and exploratory analysis to preprocessing, model building, and evaluation.
It serves as a strong mini project to showcase supervised learning skills.

## Technologies Used:

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
