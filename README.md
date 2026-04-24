# Sales Analysis Dashboard

## Project Overview

The Sales Analysis Dashboard project aims to analyze sales performance of a US-based superstore across different regions, categories, segments, and time periods. This project helps businesses understand where revenue and profit are coming from, which product categories are performing best, and how sales have trended over time across different regions of the United States.

The dataset contains transactional sales records from a US superstore covering the period from January 2014 to December 2017, including information on orders, customers, products, regions, and profitability.

---

## Project Goals

1. **Analyze overall sales performance:** Track key metrics including Total Sales, Total Profit, Total Quantity, and Average Order Value across the entire business.
2. **Understand regional performance:** Break down sales by region — Central, East, South, and West — to identify which regions contribute the most revenue.
3. **Identify top performing categories and sub-categories:** Analyze sales across Technology, Furniture, and Office Supplies categories and their sub-categories.
4. **Understand customer segments:** Compare revenue contribution across Consumer, Corporate, and Home Office segments.
5. **Track sales trends over time:** Analyze quarterly and yearly sales trends by region from 2014 to 2017.
6. **Visualize geographic distribution:** Map sales performance across all US states.

---

## Dataset

The dataset used is the Sample Superstore dataset — a US-based retail store containing order-level transaction records. Key columns include:

| Column | Description |
|---|---|
| Order ID | Unique order identifier |
| Order Date | Date the order was placed |
| Ship Date | Date the order was shipped |
| Ship Mode | Shipping method used |
| Customer ID | Unique customer identifier |
| Customer Name | Name of the customer |
| Segment | Customer segment — Consumer, Corporate, Home Office |
| Country | United States |
| City | City of delivery |
| State | State of delivery |
| Region | Region — Central, East, South, West |
| Category | Product category — Technology, Furniture, Office Supplies |
| Sub-Category | Product sub-category — Phones, Chairs, Storage, Tables, etc. |
| Sales | Total sales value of the order line |
| Quantity | Number of units ordered |
| Discount | Discount applied |
| Profit | Profit earned on the order line |
| Avg Delivery | Average delivery days |

---

## Tools Used

| Tool | Purpose |
|---|---|
| Microsoft Excel | Data cleaning and preprocessing |
| Power BI | Interactive dashboard and data visualization |

---

## Data Preprocessing (Excel)

Before building the dashboard, the dataset was cleaned in Microsoft Excel. Key steps included:

1. **Removing duplicate records:** Checked and removed any duplicate Order IDs to ensure data accuracy.
2. **Handling missing values:** Checked all columns for blank or null values and handled them appropriately.
3. **Data type formatting:** Formatted Order Date and Ship Date columns as proper Date fields. Sales, Profit, and Quantity columns were set to correct numeric formats.
4. **Avg Delivery column:** Calculated the average number of days between Order Date and Ship Date to measure delivery performance.

---

## Power BI Dashboard

An interactive Power BI dashboard titled **"Sales Analysis Dashboard"** was built to visualize all key findings. The dashboard includes:

### KPI Cards
| Metric | Value |
|---|---|
| Total Sales | 2,297K |
| Total Profit | 286K |
| Total Quantity | 38K |
| Avg Order Value | 458.6 |

### Visuals

- **Sum of Sales by Region (Pie Chart)** — Breaks down total sales across four regions. East leads with 678.78K, followed by West (725.46K), Central (501.24K), and South (391.72K).
- **Sum of Sales by Category (Bar Chart)** — Compares revenue across Technology, Furniture, and Office Supplies categories.
- **Sum of Sales by Segment (Donut Chart)** — Shows revenue split across Consumer (1.16M), Corporate (0.71M), and Home Office (0.43M) segments.
- **Sum of Sales by Sub-Category (Bar Chart)** — Highlights top sub-categories by sales — Phones, Chairs, Storage, Tables, Binders, and Machines.
- **Sum of Sales by State (Map Visual)** — Geographic map of the United States showing sales distribution across all states.
- **Sum of Sales by Year, Quarter and Region (Line Chart)** — Tracks quarterly sales trends from January 2014 to July 2017 broken down by region — Central, East, South, and West.
- **Region Slicer** — Interactive filter with four buttons — Central, East, South, West — that filters the entire dashboard by selected region.

---

## Insights and Recommendations

1. **West and East regions are the top revenue contributors**, generating 725K and 678K respectively. Marketing and inventory efforts should continue to prioritize these regions.
2. **Consumer segment dominates sales** at 1.16M — more than Corporate and Home Office combined. Consumer-focused promotions and loyalty programs can further strengthen this segment.
3. **Technology category leads in sales**, followed by Furniture and Office Supplies. New product launches and deals in the Technology category can drive significant revenue growth.
4. **Phones and Chairs are the top sub-categories** by sales. Ensuring consistent stock availability and competitive pricing for these items is critical.
5. **Sales show an upward trend from 2014 to 2017**, with noticeable peaks in Q4 each year — indicating strong holiday season demand. Seasonal campaigns should be planned ahead of Q4.
6. **South region consistently shows the lowest sales** across all years — targeted regional campaigns and partnerships can help improve performance in this region.

---

## Conclusion

This Sales Analysis Dashboard project provides a clear and interactive view of superstore sales performance across regions, categories, segments, and time periods. By using Power BI's interactive visuals and slicers, business stakeholders can quickly drill down into specific regions or time periods to make informed, data-driven decisions around sales strategy, inventory planning, and marketing investments.

---
