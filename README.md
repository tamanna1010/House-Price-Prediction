# House Price Prediction

A machine learning project to predict house prices using regression models.

## Project Overview

This project uses the California Housing dataset to build and train machine learning models that predict median house values based on various features like location, income, and property characteristics.

## Dataset

- **Source**: California Housing Dataset
- **Features**: 8 numerical features including median income, housing age, number of rooms, etc.
- **Target Variable**: Median house value
- **Total Samples**: 20,640 records

## Features

- Exploratory Data Analysis (EDA)
- Data preprocessing and feature engineering
- Multiple regression model implementations
- Model evaluation and comparison
- Hyperparameter tuning using GridSearchCV

## Project Structure

```
House-Price-Prediction/
├── data/
│   ├── housing.csv
├── notebooks/
│   └── source_code.ipynb
├── model/
│   └── final_rf_model.sav
└── README.md
└── requirements.txt
```

## Installation

1. Clone the repository
2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On macOS/Linux
   ```
3. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

For running the project, open the Jupyter notebook:
```bash
jupyter notebook notebooks/source_code.ipynb
```

## Models Used

- Linear Regression
- Random Forest Regressor
- GridSearchCV for hyperparameter tuning

## Evaluation Metrics

- Mean Squared Error (MSE)
- Cross-validation scores

## Author

Tamanna
