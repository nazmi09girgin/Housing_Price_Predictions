# Housing_Price_Predictions
This project aims to develop a model that predicts house prices. Here are the main steps of the project:

1. **Data Reading and Exploration:**
   - A dataset named "Melbourne_housing_FULL.csv" is read using the Pandas library.
   - General information and statistical summary of the dataset are examined.

2. **Data Cleaning and Preprocessing:**
   - Checking for missing values and filling them appropriately if found.
   - Dropping unnecessary columns (Bedroom2).
   - Filling missing values in some numerical columns with their mean.
   - Converting the "YearBuilt" column to an integer.

3. **Data Analysis and Visualization:**
   - Examining the correlation between prices and other features in the dataset.
   - Removing duplicate records in the dataset.
   - Performing a data cleaning process based on Z-scores, removing rows with abnormal values.
   - Creating a histogram showing the distribution of prices.
   - Generating a pair plot illustrating the relationship between price and variables such as rooms, distance, bathroom, car, land size, and building area.
   - Drawing a heatmap with a correlation matrix.

4. **Encoding Categorical Values:**
   - Using LabelEncoder to convert certain categorical columns into numerical values.
   - Dropping the relevant columns.

5. **Data Splitting and Modeling:**
   - Splitting the dataset into independent variables (X) and the dependent variable (y).
   - Creating training and test sets.
   - Building and evaluating models using various regression algorithms (Lasso, Linear Regression, Ridge, ElasticNet, KNeighborsRegressor, RandomForestRegressor, GradientBoostingRegressor, AdaBoostRegressor).

6. **Model Performance Evaluation:**
   - Evaluating the performance of models using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R2).
   - Selecting the best model based on the RMSE value.
