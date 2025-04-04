# Data Analytics Project: GPA Prediction

## Project Overview

This project uses a dataset of student performance to build a linear regression model that predicts GPA based on various factors such as parental education, study time, tutoring, parental support, and absences. The goal is to evaluate and select the best model for predicting GPA by utilizing statistical tests and visualizations to ensure the model’s validity.

## Libraries Used

Pandas: For handling and manipulating data.

NumPy: For numerical calculations.

Matplotlib & Seaborn: For data visualizations.

Statsmodels: For building and evaluating regression models.

SciPy: For performing statistical tests.

## Data Exploration
Imported the dataset and explored its structure to understand the relationships between the variables and the target variable (GPA).
Performed initial data cleaning to handle missing values and check for any inconsistencies.
### Data Visualization
Created scatterplots and pairplots to visualize relationships between the predictor variables and the target variable (GPA).
These visualizations helped identify trends, potential outliers, and the distribution of the data.
### Model Building
Built three different linear regression models using various subsets of predictors (such as parental education, study time, tutoring, and absences).
Evaluated the models based on their ability to predict GPA.
### Model Evaluation
Compared key metrics like R-squared, Akaike Information Criterion (AIC), and Bayesian Information Criterion (BIC) to determine the best-performing model.
Checked the assumptions of the linear regression model:
**Multicollinearity**: Ensured that predictors were not highly correlated with each other.
**Normality of Residuals**: Verified that residuals followed a normal distribution.
**Heteroskedasticity**: Checked for constant variance of residuals across all levels of the predictor variables.
### Assumption Checks and Outlier Detection
Tested for multicollinearity using the Variance Inflation Factor (VIF).
Checked the normality of residuals using Q-Q plots and statistical tests.
Investigated heteroskedasticity using residual plots.
Identified outliers using standardized residuals and reviewed them to ensure they didn’t unduly influence the model.
### Model Selection
Chose the best-performing model based on higher R-squared and lower AIC/BIC values.
Ensured that this model passed the residuals’ normality tests, showed no signs of multicollinearity, and had no issues with heteroskedasticity.
### Prediction
Used the best model to make predictions on new data and assess the model’s generalizability.

## Conclusion
This project demonstrates the use of linear regression to predict student GPA. The best model was selected based on statistical metrics such as R-squared, AIC, and BIC, while ensuring that all model assumptions were satisfied. The chosen model showed reliable performance, with no violations of assumptions like multicollinearity, non-normal residuals, or heteroskedasticity.

Feel free to experiment with your own dataset or make adjustments to improve the model's performance. This project serves as a practical example of how linear regression, statistical metrics, and assumption checks guide model selection and evaluation.
