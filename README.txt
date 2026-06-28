 Airline Operations Data Analysis using PostgreSQL & Power BI

Project Overview
This project analyzes airline operations data using PostgreSQL for data modeling and SQL analysis, followed by Power BI for interactive dashboard creation. The objective is to identify airline performance, flight delays, airport traffic, and operational trends.

 Project Objectives
- Analyze airline operational performance.
- Measure departure and arrival delays.
- Identify the busiest airlines and airports.
- Study monthly flight trends.
- Build an interactive Power BI dashboard for business insights.

Tools & Technologies
- PostgreSQL
- SQL
- Power BI
- Microsoft Excel
- CSV Dataset

Project Workflow
Phase 1 – Data Collection
- Collected airline operations datasets in CSV format.
- Used separate datasets for Airlines, Airports, and Flights.

Phase 2 – Data Cleaning
- Removed duplicate records.
- Handled missing values.
- Corrected data types.
- Standardized column names.
- Created a cleaned dataset (`clean_flights.csv`) for reporting.

Phase 3 – SQL Database Design & Analysis
- Created relational tables:
  - Airlines
  - Airports
  - Flights
- Defined Primary Keys and Foreign Keys.
- Performed SQL analysis using:
  - SELECT
  - WHERE
  - GROUP BY
  - ORDER BY
  - Aggregate Functions
  - JOINs
  - CASE Statements

Phase 4 – Power BI Dashboard
- Imported the cleaned dataset into Power BI.
- Created interactive visuals and KPI cards.
- Added slicers for dynamic filtering.

Dataset
The project uses four datasets:

- airlines.csv
- airports.csv
- flights.csv
- clean_flights.csv (Unable to load these datset due to large size)



The SQL analysis uses the relational tables, while the Power BI dashboard uses the cleaned dataset.

SQL Analysis Performed

- Total Flights
- Flights by Airline
- Flights by Airport
- Average Departure Delay
- Average Arrival Delay
- Monthly Flight Trend
- Airport Traffic Analysis
- Airline Performance Analysis
- Delay Analysis
- Join Operations Across Tables

Power BI Dashboard
The dashboard includes:

KPI Cards
- Total Flights
- Average Departure Delay
- Average Arrival Delay
- Total Air Distance

Charts
- Flights by Airline
- Average Departure Delay by Airline
- Monthly Flight Trend
- Flights by Destination Airport
- Weather Delay Analysis

Slicers
- Airline
- Year
- Month
- Origin Airport
- Destination Airport
- Diverted

Key Insights
- Identified airlines with the highest flight volume.
- Compared airline delay performance.
- Analyzed monthly flight trends.
- Measured airport traffic.
- Evaluated weather-related delays.
- Identified diverted and cancelled flights.

Skills Demonstrated
- SQL
- Relational Database Design
- Data Cleaning
- Data Analysis
- Data Visualization
- Power BI
- Business Intelligence
- Dashboard Design
