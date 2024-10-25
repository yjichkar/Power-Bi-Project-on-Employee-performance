# Employee Performance and Metrics Dashboard - Power BI


This repository contains a **Power BI Dashboard** that provides insights into employee performance, work habits, and departmental statistics. The dashboard focuses on visualizing key metrics across various departments and employee demographics. Below is a breakdown of the features and insights available in the dashboard:

### Key Metrics and Visualizations

1. **Departmental Overview:**
   - The dashboard allows filtering by **Department**, **Gender**, and **Education Level**, enabling dynamic segmentation of employee data based on these factors.
   - A **Tree Map** visual highlights the count of projects handled by each department, giving a quick glance at which departments handle the most workload (e.g., Customer Support, Finance, IT, Sales, etc.).

2. **Performance Score:**
   - A **Gauge Chart** displays the **Average Performance Score** across the filtered departments and demographics, providing a quick view of overall performance levels.

3. **Team and Company Metrics:**
   - **Bar Charts** show the **Count of Team Size** by department and the **Average Years at the Company** for employees in different departments. These metrics help identify team distribution and experience levels across departments.

4. **Work Habits and Training:**
   - A **Line Chart** represents the **Average Work Hours per Week** by department, showing how much time employees in different departments typically spend working.
   - Another **Line Chart** highlights the **Average Training Hours** by department, giving insights into departments that invest more in employee training.

### Data Model

- The data source for this report appears to be the **Extended Employee Performance Dataset**.
- Key columns used for this analysis include:
  - **Department**
  - **Performance Score**
  - **Team Size**
  - **Work Hours Per Week**
  - **Training Hours**
  - **Years at Company**

### Filtering and Interactivity

- The report includes slicers for:
  - **Department**
  - **Gender**
  - **Education Level**
  
  These slicers allow users to drill down into specific employee segments and customize the view according to the criteria of interest.

### Goals

- The main goal of this dashboard is to provide a comprehensive view of employee performance and workload across departments, with insights into training and work habits. It helps management make data-driven decisions to improve employee performance, balance workloads, and allocate resources effectively.

### How to Use

1. Open the `.pbix` file in Power BI Desktop.
2. Use the filters to explore employee data based on department, gender, or education level.
3. Analyze various metrics to gain insights into team sizes, performance levels, and time spent on work and training.

