

#  Sales Analysis Dashboard – Power BI

##  Introduction

This project presents an interactive **Sales Analysis Dashboard** built using **Microsoft Power BI**. It provides a comprehensive overview of sales performance across different regions, products, and time periods. The dashboard enables quick insights into revenue trends, top-performing categories, customer segmentation, and KPIs such as total sales, profit margins, and monthly growth.

---

##  Files Included

- `Sales_Analysis.pbix` – Power BI report file with complete visuals and imported data
- `Sales_Analysis.pbit` – Power BI template file (optional, without data)
- `Dashboard_Screenshot.png` – A preview of the dashboard


---

##  Key Features

- Total Sales, Profit, and Units Sold by month and region
- Dynamic filtering by product category and customer segment
- Year-over-Year comparison and percentage growth
- Top 5 performing products and customers by revenue
- Region-wise breakdown using interactive maps
- Monthly trend analysis using line chart

---

##  Dashboard_Screenshot
<img width="800" alt="Dashboard" src="https://github.com/user-attachments/assets/03f3e447-587a-43de-a015-0facbcae8696" />

---
## Key takeaways from the analysis:

- Top-Performing Products: Identified the highest revenue-generating products and categories, helping prioritize inventory and marketing strategies.
- Sales by Region: Revealed regional sales trends and highlighted high-performing states, enabling location-based decision-making.
- Revenue Growth: Tracked monthly and yearly revenue trends to evaluate the company’s growth trajectory over time.
- Customer Segments: Analyzed customer types and their impact on total revenue.
- Profitability Analysis: Used DAX to calculate profit margins and compare performance across different product categories and customer segments.
- Currency Normalization: A custom column was created to standardize foreign currency sales into a single currency (INR), using conditional logic.
All results were validated using SQL queries on the original dataset, ensuring accuracy and consistency between raw data and visual representation.

##  Data Source

The original dataset was taken from:

 [codebasics.io – Sales Insights Data Analysis Project](https://codebasics.io/resources/sales-insights-data-analysis-project)

- The data was provided in SQL format and downloaded for the analysis purposes.
- SQL queries were run to validate the output seen in Power BI.
- **DAX (Data Analysis Expressions)** was used for data manipulation, calculations, and the creation of custom measures within Power BI.

---

##  Tools & Skills Demonstrated

- Power BI Desktop  
- DAX (Calculated Columns, Measures)  
  ```
     Revenue = SUM('sales transactions'[Custom_sales_amount])
     Sales Qty = SUM('sales transactions'[sales_qty])
- SQL (Data validation and cross-checking)
- Data modeling and relationship building
- Interactive visualization design
---

##  How to Use

1. Download the `.pbix` file from this repository.
2. Open it using [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
3. Explore the visuals interactively or use filters to drill into specific segments.

 **Note**: You must have Power BI Desktop installed to open `.pbix` files.

---

##  Disclaimer

- The data used in this project is publicly available and intended solely for educational and portfolio purposes.


---

## Contact

Created by **[Shince Joseph]**  
[shincejosephv@gmail.com] 

---

