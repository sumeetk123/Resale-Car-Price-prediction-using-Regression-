## :blue_car: Used Car Price prediction using Regression
![car3](https://github.com/sumeetk123/Resale-Car-Price-prediction-using-Regression-/assets/105230723/522c0617-fa98-4dc3-b3ad-e29bc931983a)

## 🌐 Overview
In this project, we explore a dataset from CarDekho, aiming to accurately predict used car prices based on their features. We meticulously analyze and preprocess the data, utilizing polynomial regression to capture nonlinear relationships. To prevent overfitting, we employ regularization techniques. Lastly, we discuss key assumptions such as linearity, homoscedasticity, and normality, ensuring the robustness of our modeling approach.

## 🚩 Problem Statement
Estimating used car prices is complex, influenced by factors like brand, age, mileage, and condition. Leveraging polynomial regression and regularization, we enhance price accuracy. Our approach aims to provide sellers and buyers with more precise valuation insights, aiding informed decision-making.

## 🎯 Objectives
- **Data Analysis and Preprocessing**: Scrutinize the dataset and prepare it for modeling.
- **Model Building**: Construct various regression models to predict used car prices:
  - Linear Regression
  - Polynomial Regression
  - Ridge Regression
  - Lasso Regression
  - Elastic-Net Regression

## 📊 Dataset
The dataset provides a comprehensive view of used car details. Each feature of the dataset is described in the table below:

<div align="center">
<table style="width:100%">
<thead>
<tr>
<th style="text-align:center; font-weight: bold; font-size:20px">Variable Name</th>
<th style="text-align:center; font-weight: bold; font-size:20px">Description</th>
</tr>
</thead>
<tbody>
<tr><td><b><center>Car_Name</center></b></td><td>Name of the cars</td></tr>
<tr><td><b><center>Year</center></b></td><td>Year of the car when it was bought</td></tr>
<tr><td><b><center>Present_Price</center></b></td><td>Current ex-showroom price of the car</td></tr>
<tr><td><b><center>Kms_Driven</center></b></td><td>Number of kilometers the car is driven</td></tr>
<tr><td><b><center>Fuel_Type</center></b></td><td>Fuel type of car (Petrol/Diesel/CNG)</td></tr>
<tr><td><b><center>Seller_Type</center></b></td><td>Whether the seller is an Individual or a Dealer</td></tr>
<tr><td><b><center>Transmission</center></b></td><td>Gear transmission of the car (Automatic/Manual)</td></tr>
<tr><td><b><center>Owner</center></b></td><td>Number of previous owners of the car</td></tr>
<tr><td><b><center>Selling_Price</center></b></td><td>Price at which the car is being sold (Target variable)</td></tr>
</tbody>
</table>
</div>

Access the dataset on Kaggle [here](https://www.kaggle.com/nehalbirla/vehicle-dataset-from-cardekho).

## 📁 File Descriptions
- 📓 **`?.ipynb`**: The Jupyter notebook containing our analysis, preprocessing, and modeling steps.
- 📄 **`cardata.csv`**: The primary CSV file containing all the car data.
- 📘 **`README.md`**: This file, serving as a guide to the project.

