# Experience-Based Salary Prediction Using Linear Regression

## Overview
This project builds a simple machine learning model that predicts the salary of an employee based on their years of work experience. It uses a linear regression model trained on a small dataset of experience–salary pairs.

The project is part of a flipped course evaluation and demonstrates how to:
- Load and preprocess data
- Train and evaluate a regression model
- Visualize the relationship between features and target
- Use Git and GitHub for version control

## Features
- Load dataset from CSV (`experience_salary.csv`)
- Split data into training and testing sets
- Train a Linear Regression model using scikit-learn
- Evaluate model using MSE, RMSE, MAE, and R² score
- Visualize regression line and test predictions
- Predict salary for a user-given years of experience

## Technologies / Tools Used
- Python 3.x
- NumPy
- Pandas
- Matplotlib
- scikit-learn
- Jupyter Notebook / PyCharm
- Git & GitHub

## Project Structure
```text
data/               - input dataset (experience_salary.csv)
notebooks/          - Jupyter notebook for experimentation (machine.ipynb)
src/                - source code (data loading, model, evaluation, visualization)
models/             - saved model files (optional)
outputs/            - plots and metric reports (optional)
README.md           - project documentation
statement.md        - problem and scope description
requirements.txt    - Python dependencies
