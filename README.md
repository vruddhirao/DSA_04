# Sales Prediction using Machine Learning

This project involves forecasting the amount of a product that customers will purchase, taking into account various factors such as advertising expenditure, target audience segmentation, and advertising platform selection. By leveraging machine learning techniques, businesses can optimize their advertising strategies and maximize sales potential.

## Introduction

Sales prediction involves forecasting the amount of a product that customers will purchase, taking into account various factors such as advertising expenditure, target audience segmentation, and advertising platform selection. This project uses a linear regression model to predict sales based on advertising expenditure.

# Steps to Perform

Import the data
![image](https://github.com/user-attachments/assets/d111f5b0-d812-48d1-9547-7aa7bf8f5012)

Exploratory Data Analysis
We perform exploratory data analysis (EDA) to understand the distribution and relationships in the data. This includes displaying summary statistics and visualizing pair plots.
![image](https://github.com/user-attachments/assets/f106ee1f-b5ac-4188-ae1b-485f9a958281)

Model Building
We use a linear regression model to predict sales based on advertising expenditures. The data is split into training and testing sets, and the model is trained on the training set.
![image](https://github.com/user-attachments/assets/a1cf484e-6f60-45c4-91ed-727f57618100)

Evaluation
The model's performance is evaluated using Mean Squared Error (MSE) and R-squared (R²). The coefficients of the model are also displayed.
![image](https://github.com/user-attachments/assets/b94cebee-f378-4faf-b350-b5b2057b0fcc)

Visualization
We visualize the actual vs. predicted sales to understand the model's performance.
![image](https://github.com/user-attachments/assets/4e3fe5a1-02a3-4920-8589-2493394362c0)

# Results
The linear regression model provides the following coefficients and performance metrics:

TV: 0.054509
Radio: 0.100945
Newspaper: 0.004337

Performance Metrics:

Mean Squared Error (MSE): 2.908
R-squared (R²): 0.906

These results indicate that the model explains approximately 90.6% of the variance in sales, which is quite good.

Conclusion
This project demonstrates how to use machine learning techniques to predict sales based on advertising expenditures. 
The linear regression model provides a good fit with an R² value of approximately 0.906.


