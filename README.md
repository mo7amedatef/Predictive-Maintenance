# Predictive Maintenance Analysis

## Overview

This project focuses on predictive maintenance, where the goal is to forecast equipment failures using a simulated dataset. By analyzing various sensor readings and operational metrics, the project aims to predict when maintenance is required to prevent unexpected equipment breakdowns.

## Dataset

The dataset used in this project includes features such as torque, rotational speed, tool wear, and more, which are crucial for predicting equipment failure. The data was preprocessed and explored to ensure accurate and reliable analysis.

## Objectives

- Predict equipment failure based on operational data.
- Create and evaluate various machine learning models for predictive maintenance.
- Perform feature engineering to enhance the predictive power of the models.
- Compare model performance using key metrics such as accuracy, precision, recall, F1 score, and F-beta score.

## Steps Involved

1. **Data Loading and Initial Exploration:**
   - Loaded the dataset and explored its structure to understand the key features.

2. **Feature Engineering:**
   - Created new features such as power calculations and temperature differences to improve model accuracy.

3. **Exploratory Data Analysis (EDA):**
   - Visualized relationships between features and identified important patterns using Seaborn and Matplotlib.

4. **Modeling:**
   - Implemented multiple machine learning models including Logistic Regression, KNN, SVM, Decision Trees, Random Forest, and XGBoost.

5. **Evaluation:**
   - Evaluated models using confusion matrices and various performance metrics to select the most effective model for predictive maintenance.

## Tools and Libraries Used

- **Python:** Primary language for analysis.
- **Pandas:** Data manipulation and analysis.
- **NumPy:** Numerical computations.
- **Seaborn:** Data visualization.
- **Matplotlib:** Plotting and visualization.
- **Scikit-learn:** Machine learning model implementation.
- **XGBoost:** Advanced machine learning model implementation.

## Results

- Developed a predictive maintenance model with a focus on identifying equipment failure before it occurs.
- XGBoost emerged as the best-performing model with the highest accuracy and F1 score.

## How to Use

1. Clone this repository.
2. Ensure you have Python installed along with the required libraries (`pandas`, `numpy`, `seaborn`, `matplotlib`, `scikit-learn`, `xgboost`).
3. Open the `Predictive Maintenance.ipynb` notebook.
4. Run the cells sequentially to reproduce the analysis.

## Conclusion

This analysis provides a comprehensive approach to predictive maintenance, showcasing the power of machine learning in forecasting equipment failures and optimizing maintenance schedules.

