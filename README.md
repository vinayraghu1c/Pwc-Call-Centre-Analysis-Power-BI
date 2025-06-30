#  PwC Call Centre Performance Dashboard

## ![Dashboard Preview] (https://github.com/vinayraghu1c/Pwc-Call-Centre-Analysis-Power-BI/blob/main/dashboard-preview.png)

## 🔗 Live Report
[View Published Report](https://app.powerbi.com/view?r=eyJrIjoiOTg2YTZmZDUtMGE5Mi00MmQwLWIzNzUtMWEyZjM4NzViNTVmIiwidCI6ImYxMTQ1YmY3LTZmMTktNDU2Mi1hOTA1LWQxMTVlMmZiYjQ4MCJ9)

##  Project Description
This Power BI dashboard analyzes the performance of a call centre operation based on PwC dataset. The report focuses on agent efficiency, customer satisfaction, call distribution, and time-based patterns. It is fully interactive, using slicers, filters, and a clean layout designed to highlight key performance indicators.

##  DAX Measures

### Total Calls
```DAX
Total Calls = COUNT('Call Data'[Call ID])
```

### Total Call Duration (min)
```DAX
Total Call Duration (min) = SUM('Call Data'[Call Duration])
```

### Average Call Duration
```DAX
Avg Call Duration = AVERAGE('Call Data'[Call Duration])
```

### Average Customer Rating
```DAX
Avg Rating = AVERAGE('Call Data'[Customer Rating])
```

##  Visualizations Used
- KPI Cards: Total Calls, Total Call Duration, Avg Duration, Avg Rating
- Bar/Column Charts: Avg Call Duration by Agent, Ratings Distribution
- Line Charts: Trends of Calls and Ratings over time

##  Slicers and Filters

### Slicers Implemented
- Agent Name
- Topic
- Day
- Month
  
### Clear All Button
A “Clear All” button is included to instantly reset all slicers, enhancing report usability and enabling fluid exploration.

##  Key Insights
- Identified agents with highest and lowest average customer ratings
- Analyzed time-of-day patterns in call volume and duration
- Correlated long call durations with lower customer satisfaction
- Highlighted outliers in performance based on combined metrics

##  Data Cleaning and Modeling
- Removed nulls and handled missing values
- Standardized call duration in seconds
- Cleaned text fields for better grouping
- Formatted and renamed columns for readability

##  Tools and Technologies
- Power BI Desktop
- DAX (Data Analysis Expressions)
- Power Query Editor

## BY - **Vinay Raghuwanshi**  - Data and Business Analyst  
Email- vinayraghuwanshi206@gmail.com  
LinkedIn- https://www.linkedin.com/in/vinay-raghuwanshi
