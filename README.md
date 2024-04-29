# House Price Prediction using Linear Regression
This repository contains a Python script for predicting house prices using linear regression. It utilizes the scikit-learn library for machine learning tasks and pandas for data manipulation. The dataset used for training and testing the model is the King County House Sales dataset (kc_house_data.csv).

# Dependencies
Make sure you have the following dependencies installed:
- Python 3.x
- pandas
- matplotlib
- seaborn
- scikit-learn
- 
You can install the dependencies using pip:
'''bash
Copy code
pip install pandas matplotlib seaborn scikit-learn
'''

# Usage

1. Navigate to the project directory:
```bash
cd house-price-prediction
```

2. Run the Python script:
```bash
python house_price_prediction.py
```

# Description
The script performs the following tasks:
1. Data loading and exploration using pandas.
2. Data preprocessing, including checking for missing values and splitting the data into features (X) and target (Y).
3. Normalization of the features using StandardScaler.
4. Model training using Linear Regression.
5. Model evaluation using Mean Absolute Error and R-squared Score.
6. Prediction for a single house using the trained model.

# Files
kc_house_data.csv: Dataset containing information about house sales in King County.
house_price_prediction.py: Python script for predicting house prices.
README.md: Documentation file.




