Project Overview
This project involves analyzing telecommunication data from TellCo, a service provider in the Republic of Pefkakia. The goal is to identify growth opportunities and provide recommendations on whether TellCo is worth acquiring. The analysis focuses on four key areas:

User Overview Analysis

User Engagement Analysis

User Experience Analysis

User Satisfaction Analysis

The findings are presented through a web-based dashboard and a comprehensive report.

Dataset
Source: Aggregated xDR (Data Sessions Detail Record) data from a one-month period.

Features: Includes user behavior data such as session duration, total download/upload data, and application-specific usage (e.g., Social Media, Google, YouTube, Netflix, Gaming, etc.).

Dataset Link: Download Dataset

Features Description: View Features Description

Project Structure
The project is organized into the following components:

1. Data Preparation and Cleaning
Script: data_preparation.py

Tasks:

Handle missing values and outliers.

Aggregate user-level metrics (e.g., session frequency, duration, total data usage).

Perform exploratory data analysis (EDA).

2. User Overview Analysis
Script: user_overview_analysis.py

Tasks:

Identify top 10 handsets and top 3 manufacturers.

Analyze user behavior (e.g., session duration, data usage per application).

Provide recommendations for marketing teams.

3. User Engagement Analysis
Script: user_engagement_analysis.py

Tasks:

Analyze engagement metrics (e.g., session frequency, duration, total traffic).

Perform k-means clustering to classify users into engagement groups.

Visualize top 3 most used applications.

4. User Experience Analysis
Script: user_experience_analysis.py

Tasks:

Analyze network performance metrics (e.g., TCP retransmission, RTT, throughput).

Cluster users based on experience metrics.

Provide insights on device characteristics and network performance.

5. User Satisfaction Analysis
Script: user_satisfaction_analysis.py

Tasks:

Assign engagement and experience scores to users.

Calculate satisfaction scores and predict satisfaction using regression models.

Export results to a MySQL database.

6. Dashboard
Framework: Streamlit/Flask

Script: dashboard.py

Features:

Interactive visualizations of key metrics.

Summary of findings and recommendations.

Deployment: Accessible via a web browser.

Deliverables
Python Scripts: Reusable code for data preparation, analysis, and visualization.

Dashboard: Web-based interface for exploring insights.

Feature Store: Reusable features for future analysis.

Final Report: Comprehensive summary of findings and recommendations.

How to Run the Project
Clone the Repository:

bash
Copy
git clone https://github.com/your_username/your_repository.git
cd your_repository
Install Dependencies:

bash
Copy
pip install -r requirements.txt
Run Data Preparation and Analysis Scripts:

bash
Copy
python data_preparation.py
python user_overview_analysis.py
python user_engagement_analysis.py
python user_experience_analysis.py
python user_satisfaction_analysis.py
Launch the Dashboard:

bash
Copy
streamlit run dashboard.py
Access the Dashboard:

Open your browser and navigate to http://localhost:8501.

Key Findings
Top Handsets: Huawei B528S-23A dominates the market, followed by Apple and Samsung devices.

Engagement Metrics: Majority of users have low engagement, with a few high-engagement users driving significant traffic.

Data Usage: Gaming and streaming applications (e.g., YouTube, Netflix) consume the most data.

Satisfaction Scores: Engagement is the primary driver of user satisfaction.

Recommendations
Target High-Engagement Users: Focus on retaining users with high session frequency and data usage.

Optimize Network Performance: Improve TCP retransmission and RTT metrics to enhance user experience.

Marketing Strategies: Partner with top handset manufacturers (e.g., Huawei, Apple) to drive customer acquisition.

Limitations
Data Scope: Analysis is limited to one month of data, which may not capture seasonal trends.

Missing Values: Some metrics had missing values, which were imputed using mean/mode.

Device Diversity: Limited data on newer handset models.

Final Recommendation
Based on the analysis, TellCo shows potential for growth, particularly in optimizing user engagement and network performance. The investor should consider acquiring TellCo, with a focus on implementing the recommended strategies.

Contact
For questions or further assistance, please contact:

Name: Yatendra Singh

Email: yatendra803@gmail.com

GitHub: [GitHub Profile](https://github.com/yatendraFG)

This README file provides a clear overview of the project, its structure, and how to run it. Let me know if you need further adjustments!

New chat
