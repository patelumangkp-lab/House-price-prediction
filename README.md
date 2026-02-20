# House-price-prediction
This Jupyter notebook implements a Linear Regression Model to predict house prices based on the area of the house. Below is a structured overview of its contents:

# Data Loading and Visualization:
The dataset House_Price.csv is loaded using Pandas.
A scatter plot is generated to visualize the relationship between Area and Price.

# Model Training:
A LinearRegression model from sklearn is trained using the Area as the independent variable (feature) and Price as the dependent variable (target).
The model's coefficient (slope) and intercept are displayed.

# Price Prediction:
Predictions are made for specific areas (e.g., 3300 and 5000 sq ft).
A plot is generated showing the regression line fitted to the data points.

# Batch Prediction:
Another CSV file named Area.csv is read, containing a list of areas for which price predictions are generated.
The predicted prices are appended to the DataFrame and saved as Area_Price.csv.

# Visualization:
The regression line is visualized along with the data points to illustrate the model's fit.

This notebook is a clear demonstration of basic Supervised Learning with linear regression, focused on real estate pricing prediction based on property area.
