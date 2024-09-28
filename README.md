# Regression Problems - Machine Learning Project
This repository contains the solution for a project on regression problems, developed as part of the "Machine Learning" course at the University of Macedonia. The main goal is to implement and evaluate different regression models on noisy datasets, comparing their performance based on error metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).

## Project Structure
The project is divided into two main parts:

Part 1: Parametric Model Approximation
This section focuses on comparing two functions (myCustFunc and poly4thDegree) in terms of their approximation abilities on noisy datasets.

Task 1: Generate random data using a uniform distribution in the range [-4, 4].
Task 2: Define and evaluate myCustFunc with parameters λ1 and λ2.
Task 3: Generate noisy data and fit the curve using scipy.optimize.
Task 4: Compare the errors between the functions using MAE and RMSE.
Part 2: Machine Learning Approaches
In this section, three machine learning regressors are used to predict outcomes based on noisy datasets:

k-Nearest Neighbors (kNN)
Support Vector Regression (SVR)
CART Decision Tree
The steps involve:
Splitting the data into training, validation, and test sets.
Evaluating the performance of the regressors both with and without normalization.
Comparing error metrics for all regressors.
Installation
To run the project, you will need Python 3 and the following libraries:
pip install numpy matplotlib scipy scikit-learn
Usage
Data Generation: The data is generated using random uniform distributions with added noise.
Function Fitting: The myCustFunc and poly4thDegree functions are fitted using curve fitting techniques.
Regressor Training: Machine learning models (kNN, SVR, CART) are trained using the training set, and their performance is evaluated using MAE and RMSE metrics.
Running the Code
To execute the code: regression_project.py
This will generate plots and output error metrics for both parts of the project.

Results
Part 1: The poly4thDegree function showed better performance compared to myCustFunc, yielding lower error metrics.
Part 2: Initially, SVR performed best, but after normalizing the data, all regressors showed similar performance, with kNN slightly outperforming the others.
Conclusion & Future Improvements
Increasing the degree of the polynomial in Part 1 may improve performance, but it could also lead to overfitting.
Expanding the training set or using methods like cross-validation may improve regressor performance without overfitting.
