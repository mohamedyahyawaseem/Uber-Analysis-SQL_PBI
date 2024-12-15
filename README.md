# Uber Data Analyst Project

## Overview

This project demonstrates the end-to-end workflow of analyzing Uber ride-hailing data using **Excel**, **SQL**, and **Power BI Desktop**. It highlights the process of data cleaning in Excel, SQL-based data processing, and the creation of a dynamic dashboard in Power BI. The goal is to derive meaningful insights from the dataset, empowering business analysts to make data-driven decisions.

---

## Project Description

The dataset, inspired by Uber's operations, contains comprehensive information about ride bookings, including:

- **Vehicle Type**: Categories such as bikes, sedans, SUVs, etc., reflecting customer preferences.
- **Total Bookings**: Total number of rides, providing insights into overall demand.
- **Customer and Driver Ratings**: Performance metrics for drivers and satisfaction levels for customers.
- **Overall Kilometers**: Total ride distances, helping track usage patterns.
- **Booking Status**: Categories like completed, canceled, or pending rides.
- **Cancel Details**: Reasons for cancellations to identify operational bottlenecks.
- **Date and Time**: Time-series data for tracking ride demand trends.
- **Incomplete Rides**: Highlighting rides that were partially serviced.
- **Payment Methods**: Preferences such as cash, credit card, or digital wallets.

---

## Workflow Highlights

### 1. **Data Cleaning in Excel**
- **Loaded Raw Data**: Imported the dataset into Excel for preliminary inspection.
- **Cleaned Missing and Inconsistent Data**:
  - Removed rows with irrelevant or excessive missing values.
  - Standardized entries in columns like **Vehicle Type**, **Booking Status**, and **Payment Method**.
- **Applied Conditional Formatting**: Highlighted anomalies such as extreme ratings or outliers in ride distances.
- **Data Normalization**: Corrected inconsistent date and time formats for seamless time-series analysis.
- **Export to CSV**: Saved the cleaned dataset in CSV format for SQL ingestion.

### 2. **Data Processing in SQL**
- **Data Ingestion**: Imported the cleaned CSV file into a **SQL database**.
- **Schema Design**: Created a well-structured schema with appropriate data types for fields like:
  - `VARCHAR` for text fields (e.g., vehicle type, payment method).
  - `DATE` and `TIME` for temporal data.
  - `FLOAT` for numerical fields like ratings and kilometers.
- **Data Aggregation and Transformation**:
  - Calculated **Ride Completion Rates** and **Cancellation Rates**.
  - Aggregated total bookings by **Vehicle Type** and **Time of Day**.
  - Created additional metrics, such as **Average Driver Rating** and **Distance per Ride**.
- **Query-Based Insights**:
  - Identified peak booking hours and days using timestamp analysis.
  - Analyzed correlations between ratings and cancellation trends.
  - Processed data to generate KPIs for downstream visualization.

### 3. **Interactive Dashboard in Power BI Desktop**
- **Data Import**: Connected Power BI Desktop to the processed SQL dataset for visualization.
- **Dashboard Features**:
  - **Booking Status Overview**: A visual breakdown of completed, canceled, and pending rides.
  - **Customer and Driver Ratings Trends**: Distribution and trends over time.
  - **Revenue and Distance Insights**: Total revenue by vehicle type and ride distance metrics.
  - **Cancellation Analysis**: Reasons and patterns for ride cancellations.
  - **Payment Method Preferences**: Analysis of customer payment behaviors.
- **Interactivity**: Implemented slicers and filters for dynamic exploration by:
  - Time period.
  - Vehicle type.
  - Booking status or cancellation reasons.

---

## Objectives and Business Value

This project addresses key business questions:

1. **Vehicle Preferences**: Which vehicle types are most in demand?
2. **Booking and Cancellation Trends**: What are the peak booking times, and why do cancellations occur?
3. **Operational Efficiency**: How does the completion rate vary across days and vehicle types?
4. **Customer and Driver Satisfaction**: What patterns emerge from ratings?
5. **Revenue Insights**: How do payment methods and distance influence revenue?

The insights enable data-driven strategies to optimize **customer satisfaction**, **fleet management**, and **driver performance**.

---

## Skills Demonstrated

- **Excel**:
  - Data cleaning and transformation.
  - Applying conditional formatting and identifying anomalies.
- **SQL**:
  - Advanced querying for aggregating metrics and extracting insights.
  - Schema design and handling relational datasets.
- **Power BI**:
  - Creating interactive dashboards with dynamic slicers, filters, and visuals.
- **Business Analysis**:
  - Translating raw data into actionable insights and recommendations.

---

## Future Enhancements

- **Advanced Visualization**: Use geospatial maps in Power BI for location-based ride trends.
- **Machine Learning**: Predict ride demand, customer churn, and cancellation risk using advanced models.
- **Fleet Optimization**: Analyze distance and vehicle usage for operational efficiency.

---

## How to Use This Project

1. **Step 1**: Load the raw dataset into **Excel** and clean the data.
2. **Step 2**: Export the cleaned dataset to **CSV format**.
3. **Step 3**: Import the CSV file into a **SQL database** and run transformation queries.
4. **Step 4**: Connect Power BI Desktop to the SQL database and design the dashboard.
5. **Step 5**: Analyze the interactive dashboard to uncover insights.

---

## Tools and Technologies Used
- **Excel** for data cleaning and normalization.
- **SQL** for data processing, aggregation, and transformation.
- **Power BI Desktop** for visualization and dashboard creation.

---

## Conclusion

This project provides a holistic understanding of how **Excel**, **SQL**, and **Power BI** work together to analyze ride-hailing data and derive actionable insights. It is an excellent example of using data analytics to empower **business decision-making** in real-world scenarios.

---



