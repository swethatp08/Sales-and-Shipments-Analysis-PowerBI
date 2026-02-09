Sales-and-Shipments-Analysis-PowerBI 
End-to-end Power BI dashboard analyzing sales, profit, shipments, and logistics performance using DAX, time intelligence, and star-schema modeling.

Project Overview
This project focuses on analyzing sales performance, shipment volume, profitability, and logistics efficiency for a consumer goods business.The awesome chocolate.
The dashboard is designed to help stakeholders track key KPIs, identify trends, and evaluate performance across time, salespersons, and shipment sizes.


Business Questions Answered
- How are sales, profit, and shipments trending month over month?
- Which salespersons contribute the most to overall profit and profit %?
- How efficient are shipments in terms of boxes handled versus logistics effort (LBS %)?
- Are there seasonal or monthly patterns in shipment volumes?
- Which shipment sizes (box bins) occur most frequently?

---

Data Model
- Fact Table: Shipments  
- Dimension Tables: Date, Salesperson, Product, Geography  
- Schema: Star Schema  
- A dedicated "Calendar table" is used for all time-intelligence calculations.

This modeling approach ensures accurate aggregation, scalability, and optimized DAX performance.

---

Key Metrics & DAX Logic

The dashboard includes the following key measures:

- Total Sales  
- Total Profit  
- Total Cost  
- Total Boxes  
- Total Shipments  
- Month-on-Month (MoM) % Change  
- LBS % (Logistics efficiency metric)

DAX concepts used include:
- `CALCULATE`
- Time intelligence functions (`EDATE`, date comparisons)
- Filter context handling
- KPI calculations

---

Tools & Skills Used

- Power BI Desktop  
- DAX (Measures, Time Intelligence, KPIs)  
- Power Query (Data Cleaning & Transformation)  
- Data Modeling (Star Schema)  
- Business KPI Design & Analysis  

---

Dashboard Preview





