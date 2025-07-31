# 🏠 House Price Prediction using Linear Regression

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1.0%2B-orange?logo=scikit-learn)
![Status](https://img.shields.io/badge/status-Completed-brightgreen)

> Predicts **house prices** based on features like bedrooms, bathrooms, and square footage using a Linear Regression model trained on the **King County House Sales dataset**.

---

## ✨ Features

- 🧰 Uses `LinearRegression` from scikit-learn
- 🔢 Features:
  - Bedrooms
  - Bathrooms
  - Square footage (living space and lot)
  - Number of floors
- 📊 Evaluates performance with:
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R² score
- 🏡 Interactive price prediction from user input

---

## 📦 Requirements

- Python 3.8+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Install dependencies:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## 📁 Dataset
Uses ```kc_house_data.csv```

Contains historical house sales data from King County, USA

## ▶️ How to Run
1. Place ```kc_house_data.csv``` in the same folder.

2. Run the script:
   ```bash
   python main.py
3. Enter house details when prompted:
   ```bash
   Enter number of bedrooms: 3
   Enter number of bathrooms: 2
   Enter square footage of living space: 1800
   Enter square footage of lot space: 5000
   Enter number of floors: 2
   The predicted price for the house is: $478923.45
   ```
## ✅ Example Output
```bash
Mean Squared Error: 60000000000.00
Root Mean Squared Error: 244948.97
R-squared Score: 0.59
```
Note: Actual scores depend on dataset and feature scaling.

## 🧠 How It Works
- Splits data into training and test sets (80/20)

- Scales features using ```StandardScaler``` for better model performance

- Trains a Linear Regression model on scaled data

- Predicts price based on new user input, also scaled before prediction

## ✏️ Author

Built and documented by [nandhini1424](https://github.com/nandhini1424)
