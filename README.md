# Task_3
--
# Linear Regression Project

## Objective

This project demonstrates the implementation of  **Multiple Linear Regression** to predict house prices based on various features such as square footage, number of bedrooms, and age of the house. The goal is to understand how linear regression works and how to apply it to a real-world dataset.

## Tools & Libraries Used

- **Python**
- **Scikit-learn**: For implementing machine learning algorithms.
- **Pandas**: For data manipulation and preprocessing.
- **Matplotlib**: For data visualization.

## Dataset

The dataset used in this project contains various features of houses such as:
- **Square Footage**
- **Number of Bedrooms**
- **Age of the House**
- **Price** (Target variable)

You can download the dataset from the provided link or use your own dataset with similar features.

## Steps Followed

### 1. Data Preprocessing
- Loaded the dataset using **Pandas**.
- Cleaned the dataset (removed missing values if necessary).
  
### 2. Splitting the Data
- Split the dataset into **training** and **testing** sets using Scikit-learn’s `train_test_split` function.

### 3. Model Training
- Implemented **Multiple Linear Regression** to predict house prices based on multiple features.

### 4. Model Evaluation
- Evaluated the models using the following metrics:
  - **Mean Absolute Error (MAE)**
  - **Mean Squared Error (MSE)**
  - **R² Score** (coefficient of determination)

### 5. Data Visualization
- Plotted the **regression line** for the simple linear regression model.
- Visualized the **actual vs predicted prices** for the multiple linear regression model.
