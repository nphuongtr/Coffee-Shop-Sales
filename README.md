# Coffee Shop Sales Analysis

## 1. Project Overview

This project analyzes six months of coffee shop transaction data from January to June 2023. The goal is to understand sales performance, identify customer purchasing patterns, and discover business opportunities through data analysis and visualization.

Using Python, I explored sales across product categories, store locations, product types, and different time periods to answer key business questions and provide data-driven recommendations.

## 2. Business Questions

This project focuses on the following questions:

- Which product categories generate the most revenue?
- Which store locations have the highest total revenue?
- How does revenue change over time?
- During which hours does the coffee shop generate the most revenue?
- Which product types generate the most revenue?
- What is the average transaction value at each store?
- Which days of the week generate the most revenue?

## 3. Dataset Description

The dataset contains **149,116 transaction records** covering the period from January 1 to June 30, 2023.

It includes information such as:

- Transaction ID
- Transaction date and time
- Transaction quantity
- Store location
- Product category and type
- Unit price
- Product details

The dataset was used to calculate revenue and examine sales performance across different business dimensions.

**Dataset Source:** [Coffee Shop Sales Dataset – Kaggle](https://www.kaggle.com/datasets/ahmedabbas757/coffee-sales)

## 4. Tools and Technologies

- **Python** – Data analysis and calculations
- **Pandas** – Data cleaning, manipulation, and aggregation
- **Matplotlib** – Data visualization
- **Jupyter Notebook** – Analysis and documentation
- **VS Code** – Development environment

## 5. Data Preparation

The following preparation steps were performed:

- Inspected the dataset structure and data types.
- Checked for missing values and duplicate records.
- Prepared transaction date and time information.
- Created a new revenue column by multiplying transaction quantity by unit price.
- Checked for invalid quantities and prices.

**Revenue Calculation:**

`Revenue = Transaction Quantity × Unit Price`

## 6. Exploratory Data Analysis

The analysis explored sales performance across seven areas:

1. Sales by Product Category
2. Sales by Store Location
3. Monthly Revenue Trends
4. Sales by Time of Day
5. Sales by Product Type
6. Average Transaction Value by Store
7. Sales by Day of the Week

Bar charts and line charts were used to identify patterns and compare revenue across categories, locations, and time periods.

## 7. Key Findings

- **Product Categories:** Coffee and Tea were the top revenue-generating categories, contributing approximately 66.7% of total revenue.
- **Store Performance:** Hell's Kitchen generated the highest total revenue at $236,511.17.
- **Monthly Trends:** Revenue increased after February and reached its highest level in June at $166,485.88.
- **Peak Sales Hours:** The strongest sales period was between 8 AM and 10 AM, with 10 AM generating the highest hourly revenue at $88,673.39.
- **Product Performance:** Barista Espresso was the highest revenue-generating product type at $91,406.20.
- **Average Transaction Value:** Lower Manhattan had the highest average transaction value at $4.81.
- **Weekly Trends:** Average daily revenue remained relatively consistent throughout the week, with Monday recording the highest average at $3,910.66.

**Total Revenue:** $698,812.33

## 8. Business Recommendations

Based on the findings, the following recommendations could help improve business performance:

- Maintain sufficient inventory for high-performing categories, especially Coffee and Tea.
- Prioritize staffing during peak morning hours, particularly between 8 AM and 10 AM.
- Use product recommendations, combo deals, and upselling strategies to increase average transaction value.
- Monitor monthly revenue trends to support inventory and staffing decisions.
- Continue tracking store-level performance to identify opportunities for improvement.

## 9. How to Run the Project

1. Clone or download this repository.
2. Open the project folder in VS Code.
3. Install the required Python libraries:

```bash
pip install pandas matplotlib openpyxl jupyter
```

4. Download the dataset from the Kaggle link above.
5. Place the Excel file in the location expected by the notebook.
6. Open `Coffee_Shop_Sales_Analysis.ipynb` in VS Code or Jupyter Notebook.
7. Run the notebook cells from beginning to end.

**Note:** The notebook currently uses a local file path to load the Excel dataset. You may need to update the path to match your computer.

## 10. Conclusion

This project provided hands-on experience in data preparation, exploratory data analysis, data visualization, and business insight development using Python.

The analysis revealed important sales patterns across products, stores, and time periods. These insights demonstrate how data analysis can support better business decisions related to inventory management, staffing, and sales strategies.

## 11. Author

**Phuong Truong**

Data Analytics Student | Aspiring Data Analyst

[GitHub Profile](https://github.com/nphuongtr)
