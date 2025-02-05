# Mall_Customer_Segmentation

## Project Overview
You are owing a supermarket mall and through membership cards , you have some basic data about your customers like Customer ID, age, gender, annual income and spending score.

Spending Score is something you assign to the customer based on your defined parameters like customer behavior and purchasing data.

## Problem Statement
You own the mall and want to understand the customers like who can be easily converge [Target Customers] so that the sense can be given to marketing team and plan the strategy accordingly.

## Data Source
This data was obtained from [Kaggle Mall Customer  Segmentation Data](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python) also known as market basket analysis . I will be using unsupervised Machine Learning(ML) technique (KMeans Clustering Algorithm).

## Data Used
- Data: Customer Segmentation data with over 200 rows and 5 columns.
- Data Cleaning and Visualization: Python, Jupyter Notebook
- Dependencies: Numpy, Pandas, Matplotlib, Seaborn
- Model: K-Means(Unsupervised Technique)

## Summary of Findings 
1. Customers with high income and high spending scores form a distinct group.
2. Customers with low income but high spending scores belong to another group, possibly indicating impulsive spenders.
3. There are also moderate and low spenders categorized accordingly.

## Business Implications & Recommendations
1. Personalized Marketing:
 - Offer premium products & loyalty programs to Cluster 1.
 - Target Cluster 2 with exclusive discounts or product bundles.
 - Provide financing options or installment plans for Cluster 3.
2. Customer Retention Strategies:
 - Identify potential churn in Cluster 2 (high-income, low-spending) and engage them with tailored incentives.
3. Product Placement & Pricing Strategy:
 - Luxury items should be aimed at Cluster 1.
 - Budget-friendly options should be emphasized for Clusters 3 & 4.
