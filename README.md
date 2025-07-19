# Salary Prediction Web Application

## Features

- **Machine Learning Model**: Uses Random Forest Regressor for salary prediction
- **Data Preprocessing**: Handles categorical features with One-Hot Encoding
- **Visualizations**: Generates four insightful plots:
  - Actual vs Predicted Salary comparison
  - Residuals distribution
  - Feature importance
  - Scatter plot of actual vs predicted values
- **Evaluation Metrics**: Calculates and displays Mean Squared Error (MSE) and R² score

## Model Details

- **Algorithm**: Random Forest Regressor
- **Preprocessing**:
  - One-Hot Encoding for categorical features (Education, Location, Job_Title, Gender)
  - Numerical features (Experience, Age) passed through unchanged
- **Evaluation**:
  - Mean Squared Error (MSE)
  - R² score
