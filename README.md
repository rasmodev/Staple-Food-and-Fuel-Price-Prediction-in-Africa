# Predictive Analysis and Forecasting of Staple Food and Fuel Prices Across Africa
## Overview

This project focuses on predicting and analyzing the trends of staple food and fuel prices across Africa using machine learning techniques. The goal is to understand the impact of various economic factors on price fluctuations and to forecast future price trends to support effective decision-making and policy interventions.

## Project Goals

1. **Understand Price Dynamics**: Explore the factors influencing the price of staple foods and fuels across multiple African countries.
2. **Predict Future Prices**: Build and evaluate predictive models to forecast future price trends with high accuracy.
3. **Support Policy Making**: Provide insights that can inform policy decisions and strategies to address economic challenges related to food and fuel prices.

## Dataset

The dataset used in this project comes from the Famine Early Warning Systems Network (FEWS NET) and includes historical price data for staple foods and fuels. Key features in the dataset include:

| Column            | Description                                       |
|-------------------|---------------------------------------------------|
| `country`         | Country where the data was collected.            |
| `market`          | Specific market or city within the country where the product's price was recorded.           |
| `admin_1`         | Administrative region or province within the country.                 |
| `longitude`       | Longitude coordinate (geographical coordinate indicating the east-west position) of the location where the price was recorded.             |
| `latitude`        | Latitude coordinate (geographical coordinate indicating the north-south position) of the location where the price was recorded.          |
| `cpcv2`           | Product code associated with the item being priced.                                     |
| `product`         | Name of the product or commodity (staple food or fuel).                  |
| `source_document` | Source of the data document providing the price information.                    |
| `period_date`     | Date when the price was recorded.                       |
| `price_type`      | Describes the pricing type (e.g. retail, wholesale).                     |
| `product_source`  | Indicates the origin or provider of the product (e.g., Local).                                               |
| `unit`            | Unit of measurement (e.g., kg, L).                |
| `unit_type`       | Type of unit (e.g., Weight, Volume).             |
| `currency`        | Currency code for the currency in which the price is recorded (e.g., KES for Kenyan Shilling).                       |
| `value`           | Numerical value representing the price value of the product.                      |

## Methodology

To achieve the project objectives, we will follow the Cross-Industry Standard Process for Data Mining (CRISP-DM) framework, a process used to guide the machine learning lifecycle.

It is a six-phase process consisting of these key phases:

i. **Business Understanding**:
   - Understand the problem of predicting staple food and fuel prices and its significance.
   - Define the project objectives, including analyzing and forecasting food and fuel prices to support decision-making and intervention strategies for food security.

ii. **Data Understanding**:
   - Load the dataset "Staple_Food_Price_Data.xlsx".
   - Explore the dataset and variable descriptions.
   - Conduct detailed Exploratory Data Analysis (EDA), including univariate, bivariate, and multivariate analysis, and perform hypothesis testing if applicable to validate assumptions.

iii. **Data Preparation**:
   - Clean the dataset by handling missing values, duplicates, outliers, and inconsistencies.
   - Encode categorical variables and perform feature engineering to prepare the data for machine learning modeling.
   - Select relevant variables and transform data as needed to prepare the dataset for modeling.

iv. **Modeling**:
   - Split the dataset into training and validation sets to facilitate model training and evaluation.
   - Select and implement suitable regression algorithms (e.g., Linear Regression, Random Forest Regression, Gradient Boosting Regression) for predicting staple food and fuel prices.
   - Train the models on the prepared dataset.

v. **Evaluation**:
   - Assess the models' performance using metrics like RMSE and MAE.
   - Fine-tune the model hyperparameters using techniques like grid search or random search to optimize performance.
   - Use the best-performing model to make predictions on the test set.

vi. **Deployment**:
   - Deploy the trained model as a web application for real-time prediction or using .ke Streamlit, Gradio, or FastAPI.

---

By following the CRISP-DM framework, we aim to create a robust model for predicting staple food and fuel prices, leveraging detailed EDA to inform the data preparation and modeling stages, ensuring accurate and reliable predictions for stakeholders.

---
