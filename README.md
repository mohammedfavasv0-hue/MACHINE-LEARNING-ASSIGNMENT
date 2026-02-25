# Retail Sales Prediction using Machine Learning

## Project Overview

This project predicts total retail sales amount using machine learning techniques.
The goal is to analyze historical transaction data and build an accurate prediction model.

## Dataset Features

* Unit Price
* Unit Cost
* Quantity Sold
* Discount Applied
* Stock on Hand
* Category
* Store Location
* Payment Method
* Date

## Steps Performed

### Data Preprocessing

* Missing value handling
* Outlier treatment using IQR method
* Feature engineering (Year, Month, Day extraction)
* Encoding categorical variables

Final dataset shape: **(11130, 104)**

### Exploratory Data Analysis

* Correlation heatmap
* Sales distribution
* Category-wise sales
* Payment method analysis
* Sales trend over time

### Models Used

* Linear Regression
* Random Forest Regressor

### Model Performance

| Model             | MAE    | RMSE   | R² Score |
| ----------------- | ------ | ------ | -------- |
| Linear Regression | 151.16 | 232.26 | 0.81     |
| Random Forest     | 21.51  | 116.74 | 0.95     |

Random Forest achieved the best performance.

### Feature Importance

Top influencing features:

* Quantity Sold
* Unit Price
* Unit Cost
* Month
* Stock on Hand

### Conclusion

The Random Forest model predicts retail sales with high accuracy (R² = 0.95).
Pricing and quantity sold are the most important factors affecting sales.

## Technologies Used

Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## Author

Mohammed Favas
