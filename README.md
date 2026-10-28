# 🏠 House Price Prediction Using Machine Learning

## Project Overview

This project predicts house values using the California Housing dataset and Machine Learning regression algorithms. It includes data cleaning, feature engineering, model training, evaluation, and feature importance analysis.

&#x20;Objectives

- Analyze housing data.
- Handle missing values.
- Perform feature engineering.
- Encode categorical variables.
- Train and compare regression models.
- Evaluate model performance.
- Identify important features affecting house values.

## &#x20;Dataset

**File:** `housing.csv`

The dataset includes:

- Longitude and latitude
- Housing median age
- Total rooms and bedrooms
- Population and households
- Median income
- Ocean proximity
- Median house value (target variable)

## &#x20;Technologies Used

- Python
- Pandas and NumPy
- Matplotlib
- Scikit-learn
- Joblib
- JupyterLab

## &#x20;Project Workflow

1. Load and explore the dataset.
2. Check and handle missing values.
3. Create new features using feature engineering.
4. Apply One-Hot Encoding to categorical data.
5. Split data into training and testing sets.
6. Train Linear Regression.
7. Train Random Forest Regressor.
8. Evaluate models using MAE, RMSE, and R² Score.
9. Compare model performance.
10. Visualize feature importance.
11. Save the trained model using Joblib.

## &#x20;Machine Learning Models

### 1. Linear Regression

A regression algorithm used as a baseline for predicting house values.

### 2. Random Forest Regressor

An ensemble learning algorithm that combines multiple decision trees to improve prediction performance.

## &#x20;Model Evaluation Results

| Model             |       MAE |      RMSE | R² Score |
| ----------------- | --------: | --------: | -------: |
| Linear Regression | 50,888.66 | 72,668.54 |   0.5970 |
| Random Forest     | 32,338.27 | 50,382.99 |   0.8063 |

**Best Model:** Random Forest Regressor performed better on the test dataset.

## &#x20;Project Files

- `housing.csv` — Housing dataset.
- `requirements.txt` — Required Python libraries.
- `House_Price_Prediction.ipynb` — Notebook containing code and analysis.
- `house_price_model.pkl` — Saved model, if included.How to Run

1. Clone or download this repository.

2. Install dependencies:

   `pip install -r requirements.txt`

3. Open the notebook in JupyterLab.

4. Run all cells in order.

## &#x20;Future Improvements

- Hyperparameter tuning.
- Try additional regression algorithms.
- Build an interactive prediction application.
- Deploy the model as a web application. Author

**Sartaj Khan**



## &#x20;License

This project is intended for educational and learning purposes.
