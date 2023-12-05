# Diabetes-Dataset-analysis
Diabetes Dataset analysis

1)Imports the matplotlib.pyplot module and aliases it as plt. This library is used for creating visualizations, such as plots.

2)Imports the numpy library and aliases it as np. Numpy is commonly used for numerical operations and working with arrays.

3)Imports necessary modules from scikit-learn, a machine learning library. datasets provides sample datasets, linear_model contains linear regression models, and mean_squared_error is used to calculate the mean squared error.

4)Loads the diabetes dataset from scikit-learn. This dataset is often used for regression tasks.

5)Extracts the third feature (column index 2) from the diabetes dataset and reshapes it to have one additional dimension. It's selecting a specific feature for analysis.

6)Splits the dataset into training and testing sets. The last 30 samples are reserved for testing, and the rest are used for training the linear regression model.

7)Creates a linear regression model object using scikit-learn.

8)Trains the linear regression model using the training data (diabetes_x_train and diabetes_y_train).

9)Uses the trained model to predict the target values for the test data (diabetes_x_test).

10)Prints the mean squared error between the actual target values (diabetes_y_test) and the predicted values (diabetes_y_predicted). It's a measure of how well the model is performing.

11)Prints the weights (coefficients) assigned to the features by the linear regression model.

12)Prints the intercept term of the linear regression model.

13)Creates a scatter plot of the actual test data points.

14)Plots the regression line using the predicted values.

15)Displays the matplotlib plot.

![image](https://github.com/sadhanasharma1/Diabetes-Dataset-analysis/assets/117315849/e24f0dd0-891f-4a58-a89e-76c221644608)


