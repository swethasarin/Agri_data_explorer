# Agri_data_explorer

**Project Title**:AgriData Explorer: Understanding Indian agriculture with EDA
**Domain**:Agricultural(crop production statistics, yields, and farming area in India)
**Project Goal**: A data analytics and visualization project to explore, analyze, and interactively present crop production trends across Indian states and districts over the last 50 years.This project aims to empower stakeholders like farmers, policymakers, and researchers by providing actionable insights into agricultural production trends using interactive visualizations. It focuses on various crops such as rice, wheat, maize, oilseeds, soybeans, millets, and more, across Indian states.
**Project Objectives**:
1.Track and compare crop production and yield trends over time.
2.Identify high-performing states, districts, and crops.
3.Analyze crop yield efficiency and cultivated area impacts.
4.Enable dynamic exploration using filters and slicers.
**Tool/Technology Used:**
1.SQL (MySQL)-	Data extraction,Querying, EDA
2.Python-	Preprocessing and formatting,Plotly -Advanced custom visualizations
3.Power BI-	Interactive dashboards and visualizations,DAX-Creating measures
**Approach:**
1.Extracted data from the dataset, preprocessed it by cleaning the inconsistencies, handled missing values, and standardized units (e.g., hectares → ha, tons → metric tons).Also performed restructuring (including transforming wide tables into long format). 
2.Used SQL queries to extract production trends, top crops, yield metrics, and regional comparisons.
3.Separate SQL queries written for EDA questions(15) as well as for SQL questions(10) making it a total of 25 SQL queries focusing on different crops, time spans, and production metrics.
4.Created 2 dashboard, one for the EDA and the other for the SQL questions.Charts used:Line charts, bar/column charts, pie charts, maps, combo charts, scatter plots.Each crop has a dedicated dashboard page, navigated from a main homepage with crop buttons.Slicers and filters added for Year, Crop, and State selection.
**Dashboard Layout**:
**Homepage**Buttons for each crop: Rice, Wheat, Maize, Soybean, Oilseeds, etc. 
Introductory project description in a text box.
Navigation to crop-wise dashboard pages.
**Crop Pages**
Each crop has one or more visualizations:
Bar Charts for Top Producing States
Maps for geographical yield distribution
Line Charts for long-term trend analysis
Combo Charts to compare production vs. yield
Pie Charts for percentage breakdown (Top 5 states)
Scatter Plots for area vs. yield correlation
This project successfully delivers a comprehensive, interactive dashboard by combining SQL-driven data analysis with rich Power BI visualizations, it enables data-driven insights for policymakers, researchers, and farmers to make informed decisions for sustainable agricultural development.

