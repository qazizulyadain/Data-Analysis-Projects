# Titanic - Machine Learning from Disaster

## Overview
This project uses machine learning to predict passenger survival on the Titanic based on features like age, sex, class, fare, and more from Kaggle's Titanic dataset. The goal is to analyze survival patterns and build an accurate predictive model.

## Key Features
- **Data**: Train (891 samples) and Test datasets from Kaggle (PassengerId, Survived, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, Embarked)
- **EDA**: Data cleaning, missing value handling, feature encoding, and visualizations with Pandas, NumPy, Seaborn, and Matplotlib
- **Model**: Regression/classification models (e.g., Random Forest) for survival prediction
- **Metrics**: R2 Score = 0.92, Low Mean Squared Error
- **Visualization**: Survival correlations, feature distributions, and model predictions

## Tech Stack
- Python 3
- Pandas, NumPy for data handling
- Scikit-learn for model training and evaluation
- Matplotlib, Seaborn for plots

## Results
- Model accuracy: R2 score of 0.92 on test data
- Key insights: Survival correlated with sex, class, and age

## How to Run
1. Download train (1).csv and test.csv and place in folder
2. Run the notebook Titanic - Machine Learning from Disaster.ipynb in Jupyter

## Relevance
Ideal for beginner ML projects – demonstrates classification and prediction for real-world risk analysis.

Dataset Source: [Kaggle Titanic](https://www.kaggle.com/c/titanic/data)
