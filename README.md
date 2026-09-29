# Solar-Resource-Analysis-and-Machine-Learning-for-GHI-Prediction

A comprehensive data science project focused on analyzing historical solar resource data from Saudi Arabia and predicting Global Horizontal Irradiance (GHI) using multiple machine learning models.

---

## Overview

This project performs:

- Exploratory Data Analysis (EDA)
- Data preprocessing
- Missing value handling
- Outlier detection
- Feature engineering
- Machine Learning model training
- Model comparison
- Data visualization

The objective is to better understand solar resource patterns and evaluate different machine learning approaches for predicting Global Horizontal Irradiance (GHI).

---

## Dataset

The dataset contains historical solar resource measurements collected in Saudi Arabia.

Features include:

- Air Temperature
- Wind Speed
- Peak Wind Speed
- Relative Humidity
- Barometric Pressure
- Direct Normal Irradiance (DNI)
- Diffuse Horizontal Irradiance (DHI)
- Global Horizontal Irradiance (GHI)
- Geographic Coordinates
- Date & Time

---

## Data Preprocessing

The preprocessing pipeline includes:

- Removing unnecessary columns
- Handling missing values
- Linear interpolation
- Median imputation
- Forward fill for time-series values
- IQR-based outlier removal
- Datetime conversion
- Feature engineering (Year, Month, Hour)

---

## Machine Learning Models

The project compares several regression models:

- Linear Regression
- Ridge Regression
- Lasso Regression
- Random Forest Regressor
- Long Short-Term Memory (LSTM)

---

## Evaluation Metrics

Models are evaluated using:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)

---

## Visualizations

The project includes visualizations such as:

- GHI Distribution
- Air Temperature vs GHI
- Residual Plot
- Model Comparison
- Correlation Heatmap
- Monthly GHI Trends
- Solar Irradiance Density Curves
- Cumulative GHI Growth

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow / Keras

---

## Project Goals

- Explore solar resource data
- Improve data quality through preprocessing
- Predict GHI using machine learning
- Compare classical and deep learning models
- Support renewable energy research

---

## Future Improvements

- Hyperparameter tuning
- XGBoost implementation
- Cross-validation
- Interactive dashboard
- Time-series forecasting using advanced LSTM architectures

# License
 Copyright (c) 2026 Rana Althafar, Ftoon Althafar, Majd Almubarak, Sara Alruhaiman.
