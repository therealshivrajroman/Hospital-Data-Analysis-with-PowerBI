# Hospital Analysis Dashboard using Power BI

## 1. Project Overview
This project presents a comprehensive analysis of hospital operational and patient data from **January 2018 to December 2020** through an interactive Power BI dashboard.  
The primary objective is to derive actionable insights into key performance indicators (KPIs), such as patient flow, departmental costs, and treatment effectiveness.  
By visualizing complex data, the dashboard empowers hospital administrators and stakeholders to make informed, data-driven decisions to optimize resource allocation, reduce operational costs, and ultimately enhance the quality of patient care.

---

## 2. Dashboard Preview
<img width="1153" height="821" alt="image" src="https://github.com/user-attachments/assets/46173f4b-1a63-4a30-ba3b-3653832868ec" />

  
Here is a snapshot of the main dashboard interface, showcasing key metrics and interactive filters.

---

## 3. Tools Used
- **Microsoft Power BI**: The primary tool for data modeling, analysis, and visualization.
- **Power Query**: Used for data extraction, transformation, and loading (ETL) – cleaning, shaping, and preparing raw data.
- **DAX (Data Analysis Expressions)**: Used for complex calculations and custom measures (e.g., running totals, year-over-year growth, cost per patient).

---

## 4. Key Features & Insights

### 🏥 Department-wise Patient Flow
- **Patient Load Analysis**: Visualizes the number of patients treated by each department over time, identifying peak periods and traffic patterns for different Case Types (Inpatient, Outpatient, Day Case).
- **Admission & Discharge Trends**: Tracks monthly admission and discharge rates for staffing and resource planning.

### 💰 Total Treatment Costs Across Departments
- **Cost Breakdowns**: Aggregates and displays the total cost of treatments, broken down by department, medical procedure, and patient demographics.
- **Revenue vs. Cost**: Compares revenue generated against costs incurred to assess financial performance.

### 🎯 Identification of High Operational Costs
- **Cost Hotspots**: Pinpoints departments/services with high operational costs for targeted cost reduction.
- **Resource Utilization**: Analyzes critical resources (ICU beds, operating rooms) vs. costs to find inefficiencies.

### 📊 Interactive Visual Dashboards
- **User-Friendly Interface** with slicers/filters for City, Case Type, Specialty Group, and Date Range.
- **At-a-Glance KPIs**: Total Patients (18.30M), Current Year Patients (5.86M), Past Year Patients (7.27M), breakdowns by Age Profile and Adult/Child categories.

---

## 5. Dashboard Structure
- **Executive Summary**: High-level KPIs for quick insights.
- **Departmental Deep Dive**: Patient volume, costs, and average treatment duration per department.
- **Patient Demographics Analysis**: Trends by City, Age, Gender, and Admission Type.
- **Cost & Financial Analysis**: Focus on cost centers, revenue streams, and profitability.

---

## 6. Data Processing & Modeling

### Data Source
The dataset covers Jan 2018 – Dec 2020 and includes anonymized patient admissions, treatments, billing, and departmental operations.  
*(Replace with actual data source)*

### Data Transformation (Power Query)
- Removed duplicates and handled missing values.
- Standardized formats (dates, categories).
- Merged multiple sources into a cohesive dataset.
- Created calculated columns (e.g., Age from DOB, Age Groups).

### Data Model
- Implemented **Star Schema** in Power BI.
- Central fact table: **PatientStays**.
- Dimension tables: **Departments**, **Patients**, **Treatments**, **Calendar**, **City**, **SpecialtyGroup**.

---

## 7. How to Use the Dashboard
1. Open the `.pbix` file in Power BI Desktop.
2. Navigate pages via bottom tabs.
3. **Interact with Visuals**: Click any chart element to cross-filter.
4. **Use Slicers & Filters**: Filter by Date, Department, etc.
5. **Drill-Down**: Right-click visuals with hierarchy for deeper insights.

---

## 8. Potential Future Improvements
- **Predictive Analysis**: ML models for patient admission forecasts and cost predictions.
- **Real-time Integration**: Connect to live hospital systems.
- **Patient Satisfaction Analysis**: Integrate survey data to correlate efficiency with satisfaction.

---

## 📌 Author
Created by **SHIVRAJ ROMAN**  
For more projects, visit my portfolio: [SHIVRAJ QAQC Portfolio](https://therealshivrajroman.github.io/SHIVRAJ_QAQC/)

