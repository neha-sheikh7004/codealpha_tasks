# Task 2: Exploratory Data Analysis (EDA) on Global Superstore Dataset

## Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on the Global Superstore dataset. The objective is to understand the structure of the dataset, identify trends and patterns, discover business insights, detect anomalies, and validate assumptions using statistical analysis and data visualization techniques.

The analysis was performed using Python in Jupyter Notebook with the help of popular data analysis and visualization libraries.

---

## Objectives

* Understand the dataset structure and data types.
* Identify missing values and duplicate records.
* Perform data cleaning and preprocessing.
* Analyze categorical and numerical variables.
* Discover sales and profit trends.
* Explore relationships between different business variables.
* Generate meaningful business insights through visualization.
* Summarize findings and conclusions.

---

## Tools and Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## Dataset Information

The Global Superstore dataset contains information related to:

* Orders
* Customers
* Products
* Categories and Sub-Categories
* Sales
* Profit
* Discounts
* Shipping Cost
* Regions and Markets
* Order Priorities

The dataset provides a comprehensive view of business operations and sales performance across multiple regions.

---

## Project Workflow

### 1. Data Understanding

The initial phase focused on understanding the dataset structure.

Tasks performed:

* Checked dataset dimensions using `shape`
* Examined data types using `info()`
* Generated summary statistics using `describe()`
* Identified missing values
* Checked for duplicate records

---

### 2. Data Cleaning

Data quality was evaluated and necessary preprocessing steps were performed.

Tasks performed:

* Investigated missing values
* Verified duplicate records
* Converted date columns into datetime format
* Validated data types for further analysis

---

### 3. Univariate Analysis

Individual variables were analyzed to understand their distribution and characteristics.

Categorical variables analyzed:

* Ship Mode
* Segment
* Region
* Category
* Sub-Category
* Order Priority

Numerical variables analyzed:

* Sales
* Profit
* Discount
* Quantity

Visualization techniques used:

* Count Plots
* Bar Charts
* Horizontal Bar Charts
* Histograms
* Boxplots

---

### 4. Bivariate Analysis

Relationships between two variables were explored to identify patterns and business insights.

Analysis performed:

* Sales by Category
* Sales by Segment
* Profit by Category
* Profit by Region
* Sales by Region
* Discount vs Profit
* Shipping Cost vs Profit

Visualization techniques used:

* Bar Charts
* Scatter Plots

---

### 5. Correlation Analysis

Correlation analysis was performed to understand relationships among numerical variables.

Variables analyzed:

* Sales
* Quantity
* Discount
* Profit
* Shipping Cost

Visualization used:

* Correlation Heatmap

Key findings included:

* Positive correlation between Sales and Shipping Cost
* Positive correlation between Sales and Profit
* Negative correlation between Discount and Profit

---

### 6. Multivariate Analysis

Multiple variables were analyzed simultaneously to uncover deeper business insights.

Analysis performed:

* Sales by Category and Region

This helped identify category performance across different geographical regions.

---

## Key Insights

* Standard Class was the most preferred shipping method.
* Consumer segment contributed the highest customer volume.
* Central region recorded the highest order volume.
* Technology generated the highest sales and profit.
* Office Supplies had the highest order frequency.
* Binders and Storage were the most frequently ordered sub-categories.
* Most orders were categorized as Medium priority.
* Higher discounts often resulted in lower profitability.
* Most customer purchases involved small quantities.
* North Asia and Central Asia demonstrated strong sales and profit performance.
* Shipping cost alone did not guarantee higher profit.

---

## Conclusion

The Exploratory Data Analysis of the Global Superstore dataset provided valuable insights into customer behavior, sales performance, profitability, and operational trends. The analysis revealed that product categories, discount strategies, regional performance, and shipping costs significantly influence business outcomes.

The findings from this project can help businesses make informed decisions regarding pricing strategies, inventory management, customer targeting, and overall operational efficiency.

---

## Learning Outcomes

Through this project, I gained practical experience in:

* Data Cleaning
* Data Exploration
* Exploratory Data Analysis (EDA)
* Statistical Analysis
* Data Visualization
* Business Insight Generation
* Python for Data Analytics
* Working with Real-World Datasets

---

## Author

Neha Perween
