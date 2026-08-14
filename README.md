# Superstore Sales & Profitability Analysis

## Project Overview

This project analyzes e-commerce sales data to identify sales trends, profitability patterns, underperforming products, regional differences, customer-level profitability, and the relationship between discounting and profit.

The objective is to move beyond simply measuring Sales and understand **where and why profitability differs across the business**.

## Business Questions

The analysis focuses on questions such as:

* Which product categories generate the most Sales and Profit?
* Which sub-categories are underperforming?
* How does discounting relate to profitability?
* How does business performance change over time?
* Which regions perform best in terms of Sales and Profit?
* Which customers generate the highest profits or losses?
* Are high Sales always associated with high Profit?

## Tools & Technologies

* Python
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

## Analysis Performed

### 1. Data Preparation

* Loaded and inspected the dataset
* Reviewed data types and missing values
* Converted date columns to datetime format
* Created derived time-based fields for analysis

### 2. Category & Product Analysis

Compared Sales and Profit across product categories and drilled down into Furniture sub-categories.

### 3. Discount & Profitability Analysis

Analyzed the relationship between Discount and Profit and compared discount levels between profitable and loss-making customers.

### 4. Time Analysis

Analyzed yearly and monthly Sales and Profit to identify growth patterns, profitability changes, and unusually weak-performing periods.

### 5. Regional Analysis

Compared Sales, Profit, and Profit Margin across regions.

### 6. Customer Profitability

Identified the most profitable customers and customers generating significant losses.

## Key Findings

* **Technology** was the strongest category in terms of Profit.
* **Furniture** generated Sales comparable to other categories but substantially lower Profit.
* **Tables and Bookcases** were loss-making within the Furniture category.
* Higher discount levels were associated with lower profitability, with average profitability becoming negative at higher discount levels.
* Loss-making customers received an average discount of approximately **23.81%**, compared with **13.79%** for profitable customers.
* **West** was the strongest region in both Sales and Profit.
* **Central** had the lowest Profit Margin among the four regions.
* Sales generally increased over the period, but Profit Margin declined from **13.43% in 2016 to 12.74% in 2017**.
* **January 2015** was the worst-performing month, generating approximately **3.28K USD in losses**.

## Business Recommendations

1. Review high-level discounting strategies, particularly where higher discounts are associated with negative profitability.
2. Investigate the pricing, discounting, and cost structure of **Tables and Bookcases**.
3. Continue supporting profitable categories while monitoring margin rather than focusing only on Sales growth.
4. Investigate the lower Profit Margin of the **Central** region.
5. Monitor profitable growth using both Sales and Profit Margin.

## Conclusion

The analysis demonstrates that strong Sales do not necessarily translate into strong profitability. Product mix, discounting, customer behavior, regional performance, and time-based variation all contribute to differences in profitability.

The findings suggest that the business should focus not only on increasing Sales, but also on protecting Profit Margins through better discount management and closer monitoring of underperforming products, regions, and customers.
