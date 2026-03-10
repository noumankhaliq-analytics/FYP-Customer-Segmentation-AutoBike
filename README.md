# Data Analytics Customer Segmentation

## Goal of the Project
The purpose of this project is to conduct a Customer Segmentation Analysis for an Automobile Bike Company. Customer segmentation is performed by developing an RFM Model. RFM (Recency, Frequency, Monetary) analysis is a behavior-based approach that groups customers into segments based on their previous purchase transactions. In this analysis, the customer segment was divided into 11 groups. The analysis helps in determining which customer segments should be targeted to enhance sales revenue. All data quality assessment and analysis were done using Python.

---

## Analysis Approach

### 1. Data Quality Assessment and Data Cleaning
The first step towards generating useful insights from the data was **data preparation, quality assessment, and cleaning**. After cleaning, exploratory data analysis (EDA) was performed to identify customer purchasing behaviors.

**Datasets assessed and cleaned:**
- **CustomerDemographics.xlsx**: Dropped irrelevant columns, handled missing values, standardized gender column, created 'Age' and 'Age Group' features, removed outliers, checked duplicates.
- **NewCustomerList.xlsx**: Dropped irrelevant columns, handled missing values, created 'Age' and 'Age Group', checked duplicates.
- **Transaction_data.xlsx**: Converted product_first_sold_date to datetime, handled missing values, created 'Profit' feature, checked duplicates.
- **CustomerAddress.xlsx**: Standardized states column, checked for missing IDs.

---

### 2. Exploratory Data Analysis on Customer Segments
- **New vs Old Customers Age Distribution**  
  - Most customers are aged 40–49. Lowest numbers under 20 and above 80.  
  - Automobile company popular among age groups 20–29 and 40–49.  

- **Bike Purchases by Gender**  
  - Female customers account for ~51% of purchases, slightly higher than male customers.

- **Job Industry Distribution**  
  - Most new customers are from Manufacturing and Financial Services (~20%).  
  - Lowest representation from Agriculture and Telecom (~3%).

- **Wealth Segmentation by Age Category**  
  - Largest number of customers are 'Mass Customers'.  
  - 'High Net Worth' and 'Affluent' segments follow.

- **Cars Owned by States**  
  - New South Wales has most people without cars; Queensland has more car owners.

---

### 3. RFM Analysis and Customer Segmentation
Customer segmentation was done using the **RFM Model** based on previous purchase transactions.  

**Customer segments (11 groups):**
- Platinum Customers  
- Very Loyal Customers  
- Recent Customers  
- Potential Customers  
- Lost Customers  
- Losing Customers  
- Late Bloomer  
- High Risk Customers  
- Evasive Customers  
- Becoming Loyal  
- Almost Lost Customers  

---

### 4. RFM Analysis: Scatter Plots
- **Recency vs Monetary**: Recent customers purchased more products and generated higher revenue.  
- **Frequency vs Monetary**: Platinum, Very Loyal, and Becoming Loyal customers have higher frequency and monetary value.

---

## Datasets Used
- **Raw_data.xlsx**: Includes all dataset sheets  
- **Transactions_data.xlsx**: Customer transactions across states  
- **NewCustomerList.xlsx**: Newly visited customers  
- **CustomerDemographic.xlsx**: Customer demographic details  
- **CustomerAddress.xlsx**: Customer address information

---

## Tools and Technologies Used
- **Python**: Data Quality Assessment, Data Cleaning, and Exploratory Data Analysis  
- **Libraries**: pandas, matplotlib, seaborn

---

## Built With
- Python 3.8.2

---

## Author
- **Muhammad Nouman Khaliq** - [GitHub Profile](https://github.com/noumankhaliq-analytics)
