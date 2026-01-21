# Insurance - Dashboard
### 1.  Project Title
Insurance Risk And Claims Analysis
### 2.  Purpose
Project Overview This project analyzes historical insurance policy data to identify key risk factors and predict claim frequency/severity. By leveraging exploratory data analysis (EDA) and predictive modeling, the goal is to help insurance providers optimize premium pricing and identify high-risk segments.

Key Objectives:<br>
Risk Segmentation: Identifying demographic and behavioral traits that lead to higher claim costs.<br>
Loss Ratio Analysis: Calculating the relationship between premiums earned and claims paid.<br>
Predictive Modeling: Building a model to estimate the probability of a claim being filed based on policyholder attributes.<br>

Business Impact In the insurance industry, profitability relies on the "Loss Ratio." This project focuses on lowering that ratio by:
Early Warning: Detecting patterns in "Frequency" (how often claims happen) and "Severity" (how expensive they are).<br>
Pricing Optimization: Highlighting segments where premiums may be underpriced relative to their risk profile.<br>
### 3.	Tech Stack
The dashboard was built using the following tools and technologies:<br>
•	📊 Power BI Desktop – Main data visualization platform used for report creation.<br>
•	📂 Power Query – Data transformation and cleaning layer for reshaping and preparing the data.<br>
•	🧠 DAX (Data Analysis Expressions) – Used for calculated measures, dynamic visuals, and conditional logic.<br>
•	📝 Data Modeling – Relationships established among tables (resorts, snow, and data_dictionary) to enable cross-filtering and aggregation.<br>
•	📁 File Format – .pbix for development and .png for dashboard previews.
### 4.	Data Source
Source: Ski-resort-stats.com & NASA Earth Observations. 
### 5.	Features 
• Business Problem
Insurance providers face significant financial pressure due to unpredictable claim patterns and diverse risk profiles. Without a centralized way to analyze how demographic factors (age, education), vehicle details (make, age), and usage (commercial vs. personal) correlate with financial losses, insurers struggle to price premiums accurately and identify high-risk segments.<br>
This is a comprehensive breakdown of your Insurance Risk & Claims Analysis project. Using the same structured format as the ski resort example, I have synthesized your domain document and business requirements into a professional project summary.<br>

• Business Problem<br>
Insurance providers face significant financial pressure due to unpredictable claim patterns and diverse risk profiles. Without a centralized way to analyze how demographic factors (age, education), vehicle details (make, age), and usage (commercial vs. personal) correlate with financial losses, insurers struggle to price premiums accurately and identify high-risk segments.<br>

Key questions include:<br>
Which car makes and usage types contribute most to the total claim payout?<br>
How does the presence of "Kids Driving" in a household impact risk frequency?<br>
Are there specific geographic "Coverage Zones" that are underperforming or prone to higher claims?<br>
Which customer demographics (Education/Marital Status) represent the most stable policyholders?<br>

• Goal of the Dashboard<br>
To deliver a centralized, interactive Power BI tool that:<br>
Monitors Financial Exposure: Tracks claim severity and frequency in real-time.<br>
Refines Underwriting: Uses demographic and vehicle data to optimize premium pricing.<br>
Segment Customers: Identifies high-value vs. high-risk profiles for targeted marketing and risk mitigation.<br>

• Walkthrough of Key Visuals<br>
Key KPIs (Top Header)<br>
Total Policies: The scale of the active customer base.<br>
Total Claim Amount: The total financial impact of losses.<br>
Claim Frequency: The average number of claims filed per policy.<br>
Average Claim Amount: Measure of claim severity (Risk Exposure).<br>
Gender-wise Split: High-level demographic distribution.<br>
Core Visualizations<br>
Policy & Claim Distribution (Donut Charts): Analyzes data by Car Use (Commercial vs. Personal) and Coverage Zone (Urban vs. Rural) to pinpoint environmental risk.<br>
Risk by Manufacturer (Bar Chart): Ranks Car Makes by claim volume to identify brands that are more expensive to insure.<br>
Age & Vehicle Lifecycle (Histogram & Area Chart): * A histogram of Age Groups identifies peak claim years for drivers.<br>
An area chart of Car Year tracks how vehicle aging affects policy count and repair costs.<br>
Household Dynamics (Ribbon Chart): Visualizes the impact of Kids Driving on total claims, showing how risk shifts as more young drivers are added to a household.<br>
Socio-Economic Profiles (Matrix Heat Grid): A cross-analysis of Education & Marital Status to find "safe harbor" customer segments.<br>

• Business Impact & Insights<br>
Premium Optimization: Actuaries can adjust rates for high-risk categories, such as commercial vehicles in urban zones or households with multiple young drivers.<br>
Fraud Detection: By identifying outliers in the "Average Claim Amount" vs. "Car Color" or "Car Make," investigators can flag unusual patterns for review.<br>
Marketing Strategy: Marketing teams can target "Low-Risk" profiles (e.g., highly educated, married policyholders) with loyalty discounts.<br>
Operational Efficiency: Provides stakeholders with a "single source of truth," moving away from scattered data sources to a unified reporting system.<br>
### 6.	Screenshots
Show what the dashboard looks like. - ![Alt text](https://github.com/username/repo/assets/image.png)
[Dashboard Preview]
