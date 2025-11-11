Blinkit Sales Analysis

This repository contains a data analysis of sales data from the quick-commerce company Blinkit, performed using Python in a Jupyter Notebook. The analysis explores various factors influencing sales to derive actionable insights.

1. Problem Statement

The objective of this analysis is to investigate sales data from Blinkit outlets to identify key factors that influence product sales. The analysis aims to understand how various product attributes (such as item type, fat content) and outlet characteristics (including size, location, type, and establishment year) correlate with sales performance. The ultimate goal is to uncover patterns that can help optimize sales and marketing strategies.

2. Dataset

The analysis is based on the blinkit_data.csv file.

Data Source: The dataset can be accessed via Google Drive here: [https://docs.google.com/spreadsheets/d/17p4UfrUCc2BysbOqq82vB_4pIYrKukcVe15ckMGCVAc/edit?usp=sharing]

The dataset includes the following key features:

Item Fat Content: Category of fat content (e.g., Low Fat, Regular).

Item Type: The category the product belongs to (e.g., Fruits and Vegetables, Frozen Foods).

Outlet Establishment Year: The year the outlet was established.

Outlet Location Type: The type of city/area where the outlet is located (e.g., Tier 1, Tier 3).

Outlet Size: The size of the outlet (e.g., Medium, Small, High).

Outlet Type: The type of outlet (e.g., Supermarket Type1, Grocery Store).

Item Visibility: The display area percentage of the product.

Item Weight: The weight of the product.

Sales: The total sales for the product in that specific outlet.

Rating: The customer rating of the product.

3. Analysis & Key Insights

The analysis performs data cleaning, calculates key performance indicators (KPIs), and visualizes relationships between sales and various features.

Key Questions Explored:

Overall Performance: What are the total sales, average sales, and average product rating?

Product-Level Sales:

How do sales break down by item type?

What is the influence of fat content (Low Fat vs. Regular) on total sales?

Outlet-Level Sales:

Which outlet locations and sizes generate the most sales?

Is there a sales trend based on the outlet's establishment year?

How do sales differ between outlet location types when considering item fat content?

Visualizations Included:

Total Sales by Fat Content (Pie Chart)

Total Sales by Item Type (Bar Chart)

Total Sales by Outlet Location Type and Item Fat Content (Grouped Bar Chart)

Total Sales by Outlet Establishment Year (Line Chart)

Total Sales by Outlet Size (Pie Chart)

Total Sales by Outlet Location Type (Bar Chart)

4. Technologies Used

Python 3

Pandas: For data manipulation and analysis.

NumPy: For numerical operations.

Matplotlib & Seaborn: For data visualization.

Jupyter Notebook: As the development environment.