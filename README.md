#  House Price Prediction Using Machine Learning

##  Project Overview

This project aims to predict house prices using Machine Learning techniques based on various property features such as area, number of bedrooms, bathrooms, parking spaces, furnishing status, and other amenities. The project demonstrates the complete machine learning workflow, including data preprocessing, exploratory data analysis, model building, evaluation, and visualization.

---

##  Objective

The primary objective of this project is to develop a regression model that accurately predicts house prices and identifies the key factors influencing property values. Two regression algorithms are implemented and compared to determine the better-performing model.

---

##  Dataset

- **Dataset Name:** Housing Prices Dataset
- **Source:** Kaggle
- **File Used:** `Housing.csv`

The dataset contains information about residential properties, including:

- Price (Target Variable)
- Area
- Number of Bedrooms
- Number of Bathrooms
- Number of Stories
- Parking Availability
- Main Road Access
- Guest Room
- Basement
- Hot Water Heating
- Air Conditioning
- Preferred Area
- Furnishing Status

---

##  Technologies Used

- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

##  Project Workflow

### 1. Data Loading
- Imported the housing dataset using Pandas.
- Explored the dataset structure and statistical information.

### 2. Data Preprocessing
- Checked for missing values.
- Removed duplicate records.
- Converted categorical variables into numerical format using One-Hot Encoding.
- Prepared the dataset for model training.

### 3. Model Building
Two regression models were developed:

- Linear Regression
- Random Forest Regressor

The dataset was divided into training and testing sets using an 80:20 ratio.

### 4. Model Evaluation
The models were evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

The performance of both models was compared to identify the better predictor.

### 5. Data Visualization
The following visualizations were created:

- Distribution of House Prices
- Correlation Heatmap
- Actual vs Predicted Prices
- Feature Importance (Random Forest)

---

##  Results

The Random Forest Regressor achieved better prediction accuracy compared to the Linear Regression model by producing lower prediction errors and a higher R² Score.

The analysis revealed that property area, number of bathrooms, parking availability, and furnishing status are among the most influential factors affecting house prices.

---

##  Project Structure

```
HousePricePrediction_SnehaKompelli/
│
├── analysis.ipynb
├── Housing.csv
├── summary.docx
├── README.md
└── charts/
    ├── histogram.png
    ├── heatmap.png
    ├── prediction.png
    └── feature_importance.png
```

---

##  Future Enhancements

- Implement advanced regression algorithms such as XGBoost and Gradient Boosting.
- Perform hyperparameter tuning for improved model performance.
- Build an interactive web application using Streamlit or Flask.
- Deploy the trained model for real-time house price prediction.

---

##  Author

**Sneha Kompelli**
