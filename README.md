# House Price Prediction Model with Python

## Project Overview
The given Python code demonstrates a complete workflow for a housing price prediction model using the kc_house_data dataset. This dataset contains various features about houses such as the number of bedrooms, bathrooms, living area size, and more, which are used to predict the house prices. Here’s a detailed description of the code:

## Workflow Steps
1. **Data Loading and Exploration:**
   - The code starts by importing the necessary libraries (pandas for data manipulation, xgboost for machine learning, and matplotlib for visualization).
   - The dataset is loaded from a CSV file named kc_house_data.csv into a pandas DataFrame.
   - Basic information about the dataset such as the number of entries and data types is shown using data.info().
   - Missing values are checked, and summary statistics are obtained.

2. **Feature Selection:**
   - Relevant features for the model are selected, and the target variable is defined.
   - The features include 'bedrooms', 'bathrooms', 'sqft_living', 'sqft_lot', 'floors', 'waterfront', 'view', 'condition', 'grade', 'sqft_above', 'sqft_basement', 'yr_built', 'yr_renovated', 'zipcode', 'lat', 'long', 'sqft_living15', and 'sqft_lot15'.
   - The target variable is 'price'.

3. **Data Splitting:**
   - The dataset is split into training and testing sets using the train_test_split function from sklearn.model_selection.

4. **Model Training:**
   - XGBoost library is used to create and train a regression model.
   - Model parameters such as the objective function (reg:squarederror) and evaluation metric (rmse) are defined.
   - The model is trained with 100 boosting rounds.

5. **Model Evaluation:**
   - Predictions are made on the test set, and the model's performance is evaluated using the Root Mean Squared Error (RMSE) metric.

6. **Visualization:**
   - Actual vs. predicted prices for both training and test sets are plotted using matplotlib.
  
7. **Prediction for a Single Instance:**
   - The code also demonstrates how to predict the price for a single new house by creating a DataFrame with the required features and passing it through the trained model.

This code provides a comprehensive example of building a machine learning model for house price prediction, including data loading, preprocessing, feature selection, model training, evaluation, and visualization.

## Contact

Feel free to reach out if you have any questions or suggestions:

- **LinkedIn**: [Priyadharshini NRS](https://www.linkedin.com/in/priyadharshininrs)
- **Email**: priyadharshininrs@gmail.com
