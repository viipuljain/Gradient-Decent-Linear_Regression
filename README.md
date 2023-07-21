# Boston DataSet - Gradient Descent Algorithm
## Overview
In this project, we implement a Gradient Descent algorithm to predict the net hourly electrical energy output (EP) of a Combined Cycle Power Plant using the Boston dataset from sklearn. The dataset contains 9568 data points collected over 6 years (2006-2011), with hourly average ambient variables such as Temperature (T), Ambient Pressure (AP), Relative Humidity (RH), and Exhaust Vacuum (V).

## Implementation
1.Gradient Descent Algorithm:
We have coded a Gradient Descent algorithm capable of handling N features. The algorithm iteratively updates the model parameters to minimize the Mean Squared Error (MSE) between the predicted values and the actual values in the training dataset (X train and Y train). This helps us achieve accurate predictions for the test dataset.

2.Hyperparameter Tuning:
We experimented with various combinations of learning rates and the number of iterations to optimize the algorithm's performance. This step ensures we find the best values to balance convergence speed and prediction accuracy.

3.Feature Scaling:
Feature scaling was applied to the input features to normalize their ranges and enhance the algorithm's performance. By scaling the features, we aimed to obtain better results and improve the convergence rate of Gradient Descent.

## Instructions
1.The code for the Gradient Descent algorithm can be found in the gradient_descent.py file.

2.To test different combinations of learning rates and iterations, adjust the hyperparameters in the code and observe their effects on the predictions.

3.To enable feature scaling, use the StandardScaler or MinMaxScaler from sklearn before feeding the data into the Gradient Descent algorithm.
