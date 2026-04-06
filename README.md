# Bike-buyer-analysis-oluwabusola

## Project Overview
This project aims to identify the demographic characteristics of customers who are most likely to purchase a bicycle. By analyzing factors such as income, age, marital status, and commute distance, I developed a data-driven profile of the "ideal" bike buyer to help target marketing efforts more effectively.

## Dataset
The dataset consists of 1,000 records of potential bike buyers with several attributes:
- **Demographics:** Gender, Marital Status, Education, Occupation, Income, Children, Home Ownership.
- **Logistics:** Cars Owned, Commute Distance, Region, Age.
- **Target Variable:** Purchased Bike (Yes/No).

## Tools Used
- **Excel:** Data Cleaning, Pivot Tables, and Dashboard Design.
- **GitHub:** Project Documentation and Version Control.

## Data Cleaning Process
Before analysis, the raw data underwent a rigorous cleaning process to ensure accuracy:
1.  **Handling Missing Values:** Filled null values in critical columns like `Income`, `Gender`, and `Age` using median/mode imputation or logical deduction based on related fields.
2.  **Duplicate Removal:** Identified and removed duplicate records based on `ID`.
3.  **Standardization:** Cleaned the `Marital Status` (M/S to Married/Single) and `Gender` (M/F to Male/Female) columns for better readability.
4.  **Data Categorization:** Created an **Age Bracket** column to group customers into:
    * *Young Adult* (Under 31)
    * *Middle-Aged* (31–54)
    * *Old* (55+)
5.  **Formatting:** Adjusted currency for `Income` and ensured `Commute Distance` was logically ordered.

## Key Insights
After analyzing the data through pivot tables, several trends emerged:

### 1. Income & Gender
* **Insight:** On average, customers who purchased a bike had a higher income ($\$57,505$) compared to those who did not ($\$54,874$).
* **Trend:** Male buyers generally have a higher average income than female buyers across both categories.

### 2. Age Demographics
* **Insight:** The **Middle-Aged** bracket (31–54) is the primary market for bike sales, accounting for the highest volume of purchases.
* **Trend:** While Young Adults have a high conversion rate relative to their population size, the "Old" category shows the lowest interest in bike purchases.

### 3. Commute Distance
* **Insight:** People with a commute of **0–1 miles** are the most likely to purchase a bike.
* **Trend:** As commute distance increases (especially beyond 10 miles), the likelihood of purchasing a bike significantly drops.

### 4. Regional Performance
* **Insight:** **North America** represents the largest market share, though the **Pacific** region shows a higher percentage of "Yes" responses relative to its total sample size.

## Dashboard
The final output of this project is an interactive Excel Dashboard that allows stakeholders to filter data by Region, Education, and Marital Status. 


<img width="1366" height="768" alt="Screenshot (93)" src="https://github.com/user-attachments/assets/d5e8b919-8f1b-4334-9d07-0c9461fb3e06" />

## Recommendations
Based on the analysis, the following marketing strategies are recommended:
- **Targeted Ads:** Focus marketing spend on middle-aged professionals in North America earning above $\$55,000$.
- **Short-Commute Campaigns:** Create "Commute to Work" campaigns specifically targeting individuals living within 1–2 miles of their workplace.
- **Product Alignment:** For the Pacific region, emphasize premium models as the conversion rate is high despite a smaller total population.

---

### How to use this repository
1. **Raw Data:** View [bike_buyers.csv](https://github.com/user-attachments/files/26522043/bike_buyers.csv) to see the initial dataset.

Cleaned Data: See [bike_buyers_clean.csv](https://github.com/user-attachments/files/26522064/bike_buyers_clean.csv) for the processed data used in the analysis.

Analysis: open [bike buyer data.xlsx](https://github.com/user-attachments/files/26522069/bike.buyer.data.xlsx)
to interact with the Pivot Tables and Dashboard.
