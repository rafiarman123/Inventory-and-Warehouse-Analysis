
### Project Title / Headline

📦 **Inventory & Warehouse Outlook: Global Logistics & Operations Dashboard**

An interactive Power BI dashboard for monitoring global warehouse performance, tracking inventory turnover, reducing backorders, and optimizing regional fulfillment operations.

---

### Short Description / Purpose

The **Inventory & Warehouse Outlook Dashboard** provides supply chain and operations managers with end-to-end visibility into global inventory metrics. It streamlines stock allocation, pinpoints supply chain bottlenecks, and evaluates metrics like lead time, days sales of inventory (DSI), and warehouse capacity utilization to drive data-informed operational decisions.

---

### Tech Stack

* 📊 **Power BI Desktop** – Core data visualization platform used for report building and interactive dashboards.


* 📂 **Power Query** – ETL tool used for data cleaning, transformation, and structural preparation.


* 🧠 **DAX (Data Analysis Expressions)** – Used for custom measures, operational KPIs, dynamic aggregations, and ratios.


* 📝 **Data Modeling** – Optimized data schema establishing relationships between regional stock, fulfillment statuses, and product metrics.


* 📁 **File Format** – `.pbix` for report development and `.png` for dashboard documentation previews.



---

### Data Source

* **Source:** Enterprise Supply Chain & Logistics Database.


* **Dataset Scope:** Operational warehouse records tracking 4 core product categories (**Accessories, Clothing, Electronics, Furniture**) across 4 global regions (**North, West, East, South**) from 2020 through 2024. Includes fulfillment status, transportation volumes, lead times, and capacity thresholds.



---

### Features / Highlights

#### Business Problem

Unbalanced stock, unmonitored backorders, and warehouse space inefficiencies increase holding costs and lead to lost sales revenue. Operations teams often struggle to quickly evaluate warehouse capacity, regional lead times, and stock turnover without manual effort.

#### Goal of the Dashboard

* Provide immediate visibility into global inventory health and operational performance.


* Highlight fulfillment bottlenecks across regional warehouses and product categories.


* Support dynamic cross-filtering by region and category for fast operational decision-making.



#### Key Visuals Breakdown

* **Core KPI Cards:**
* **Warehouse Utilization:** `34.08%` (Active storage occupancy against capacity).


* **Days Sales of Inventory (DSI):** `15.56 days` (Average days to convert stock to sales).


* **Inventory Turnover Ratio:** `23.47` (Efficiency rate of inventory replacement).




* **Filter Slicers:** Dynamic drop-downs to filter all visuals by **Region** and **Category**.


* **Warehouse Utilization Gauge:** Tracks occupancy (`34.08`) against target operational capacity (`75.00` operational target, `100.00` total capacity).


* **Transportation by Category and Region (Clustered Column Chart):** Displays shipment distributions across North, West, East, and South regions.


* **Sum of Units Sold by Year (Area Chart):** Historical sales trends from 2020 to 2024, showing steady growth reaching `198K` units.


* **Average Lead Time by Category (Donut Chart):** Breaks down fulfillment speeds (average `15.74 days` globally, ranging from `15.29 days` for Clothing to `16.60 days` for Accessories).


* **Count of Backorder by Order Status (Bar Chart):** Monitors backorder resolution (`838 Fulfilled`, `248 Pending`, and `114 Canceled`).


* **Inventory Level by Region and Category (Bar Chart):** Maps stock density per category across all 4 operational regions.



#### Business Impact

* **Order Fulfillment Optimization:** Expedites resolution of pending backorders to minimize cancellations.


* **Inventory Balancing:** Identifies stock imbalances across regions to optimize reordering and lower holding costs.


* **Capacity Planning:** Monitors underutilized warehouse space to maximize operational throughput.



---

### Screenshots / Demos
Show what the dashboard looks like. - ![Alt_text](https://github.com/username/repo/assets/image.png)
Example: ![Dashboard_Preview](https://github.com/rafiarman123/Inventory-and-Warehouse-Analysis/blob/main/Inventory%20and%20Warehouse%20Outlook.png)
