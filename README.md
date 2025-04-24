# Data Visualization & Storytelling Report

**Tool Used:** Power BI  
**Dataset:** `train.csv` (Source: Kaggle)

---

## **Objective**
To create a visual report that effectively communicates business insights through charts and graphs, following best practices of data storytelling.

---

## **Steps Followed**

### 1. **Data Preparation**
- Loaded the `train.csv` dataset from **Kaggle** into Power BI.
- Cleaned the dataset by:
  - Removing **null values**, **blank rows**, and **duplicate rows**
  - Adjusting **data types** for proper analysis
  - Using **locale formatting** to correctly parse dates
- Created new columns and measures:
  - `OrderMonth`, `OrderYear`, `YearMonth` (for trend analysis)
  - `Avg Sales per Order`
  - `Total Orders`
  - `Total Sales`
  - `Profit`
  - `Delivery Days` (calculated using DATEDIFF between `Ship Date` and `Order Date`)

---

## **Visualization Storyboard**

#### **Page 1: Sales Overview**
- Total Sales (Card)
- Monthly Sales Trend (Line Chart)
- Sales by Region (Bar Chart)

**Insight:**  
Sales peaked in **Nov 2018**, especially in the **West** region.

---

#### **Page 2: Category & Sub-Category Performance**
- Sales by Category (Bar Chart)
- Sales by Sub-Category (Column Chart)

**Insight:**  
**Technology** is the **top-performing category**.

---

#### **Page 3: Segment Analysis**
- Sales by Segment (Pie Chart)
- Profit by Segment (Column chart)

**Insight:**  
The **Consumer segment** had the **highest sales volume**.

---

#### **Page 4: State/City-wise Sales**
- Top 10 States by Sales (Column Chart)

**Insight:**  
**California** generated the **most revenue**.

---

#### **Page 5: Shipping Mode Insights**
- Orders by Ship Mode (Column Chart)
- Average Delivery Days by Ship Mode (Bar Chart)

**Insight:**  
**Standard Class** was the **most used**.  
Average delivery time for **Standard Class** is around **5.01 days**.

---

#### **Page 6: Summary**
- KPIs (Total Sales, Avg Sales per Order, Total Orders)
- Summary of all key insights

---

## **Export**
- Report exported to PDF as `Sales_Data_Report.pdf`.

---

## **Conclusion**
This task helped demonstrate the power of **visual storytelling** by turning raw data into **actionable business insights** through charts and KPIs in Power BI.

---
