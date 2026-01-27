# Housing Prices Exploratory Data Analysis (EDA)

## Project Overview

This project focuses on **Exploratory Data Analysis (EDA)** of a **Housing Prices dataset for Hyderabad**. The goal is to understand how various factors such as **area, location, number of bedrooms, and bathrooms** influence housing prices. Through statistical analysis and visualizations, the project uncovers patterns, trends, and anomalies that help in understanding the real-estate market behavior.

This analysis is suitable for **data analysis beginners, academic projects, and interview portfolios**.

---

## Objectives

* Identify key patterns and trends in housing prices
* Understand relationships between important variables
* Detect anomalies, outliers, and data quality issues
* Discover insights related to price variation across locations
* Prepare clean and reliable data for further modeling

---

## Dataset Description

The dataset contains residential property listings from **Hyderabad**.

### Key Columns

* **Price**: Total price of the house or property
* **Area (sq.ft)**: Built-up area of the property
* **Location**: Locality within Hyderabad
* **Bedrooms / BHK**: Number of bedrooms
* **Bathrooms**: Number of bathrooms
* **Resale**: Indicates resale or non-resale property

---

## Data Understanding

* `df.shape` was used to understand the size of the dataset
* `df.info()` helped identify data types and missing values
* `df.describe()` provided statistical summaries for numerical columns
* Categorical summaries were generated to understand location and resale distributions

---

## Data Cleaning

* No missing values were found, indicating good data quality
* Duplicate records were identified and removed
* Invalid values representing uncertain data were carefully handled
* Location column was converted from **object** to **category** for memory optimization

---

## Exploratory Data Analysis

### Univariate Analysis

* Most properties have **2 or 3 bedrooms**, with 3 BHK being the most common
* Higher bedroom count properties (4+) are limited
* Price distribution is **right-skewed**, indicating fewer luxury properties
* Area values are mostly concentrated within a common range, with some large outliers

### Bivariate Analysis

* Strong positive correlation between **Area and Price**
* Location significantly impacts property prices
* Average and median prices vary widely across different localities
* Resale and non-resale property distributions differ by location

---

## Visualizations Used

* Price distribution plots
* Area vs Price scatter plots
* Bar plots for average prices by location
* Stacked bar charts for resale vs non-resale properties

These visualizations clearly highlight pricing trends, outliers, and location-based variations.

---

## Key Insights

* Property prices strongly depend on **area and location**
* Larger houses tend to have proportionally higher prices
* Certain locations consistently fall under **premium price ranges**
* The dataset includes affordable, mid-range, and luxury properties
* A healthy resale market exists across multiple localities

---

## Challenges Faced

* Presence of invalid values that required careful cleaning
* High price variability made outlier detection important
* Some locations had fewer data points, limiting deep comparison

---

## Conclusion

The EDA provided a clear understanding of the dataset structure, quality, and pricing behavior. After handling duplicates and invalid values, the dataset became reliable for analysis. The insights derived from univariate and bivariate analysis can support **real-estate decision-making** and serve as a strong foundation for **predictive modeling** in future work.

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook
