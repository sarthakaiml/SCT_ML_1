# 🏡 SCT_ML_1: House Price Prediction (Linear Regression)

## Task Objective
Implement a Linear Regression model to predict the prices of houses based on their square footage, and the number of bedrooms and bathrooms.

## File Contents
- **Task_01_House_Price_Prediction.ipynb**: Jupyter Notebook containing the Python code, model training, and the final results/analysis.

---

## 📈 Model Performance Analysis

The model was trained on a simulated dataset to demonstrate the use of multivariate linear regression.

### Performance Metrics
| Metric | Value | Interpretation |
| :--- | :--- | :--- |
| **R-squared (R2 Score)** | **0.8046** | This indicates that **80.46%** of the variation in house prices is explained by the features (SqFt, Bedrooms, Bathrooms), demonstrating a strong fit. |
| **Mean Squared Error (MSE)** | 2,282,923,141.15 | The average squared difference between actual and predicted prices. |

### Model Coefficients
The coefficients indicate the estimated price increase for a one-unit change in the feature:
* **SqFt Coefficient:** **$87.89**
* **Bedrooms Coefficient:** **$53,477.55**
* **Bathrooms Coefficient:** **$31,020.13**

### Example Prediction
The model provided a reasonable prediction for a test house:
* **Actual Price:** $593,710.13
* **Predicted Price:** $538,381.39
