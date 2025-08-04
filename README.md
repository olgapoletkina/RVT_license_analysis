# Revit License Usage Analysis

This project aims to analyze Revit license usage patterns within the company to determine the optimal number of licenses required. By examining data on employee login and logout times from license logs, we can identify key users and trends in Revit software usage across different days and times.

## Project Goals
The primary goal is to assist the company in making informed decisions regarding Revit license purchases. Specifically, we aim to:

- Identify top users and frequent Revit usage patterns.
- Analyze workday structures, including start, end, and duration of Revit sessions.
- Determine the minimum number of licenses required based on current usage patterns.

## Methodology
1. **Data Collection**: License logs were parsed to capture relevant timestamps and actions (IN, OUT, DENIED) for Revit license usage.
2. **Data Cleaning and Transformation**: The raw log data was processed to extract date, time, user ID, license status, and other key information. This step involved removing unnecessary information and standardizing the data format.
3. **Data Analysis**: Several analyses were performed to understand Revit usage patterns:
   - **Unique Daily Users**: Counted the unique users each day to understand daily demand.
   - **Top Users Identification**: Analyzed individual users' frequency and duration of Revit usage to identify key users.
   - **Workday Analysis**: Examined typical start and end times and the duration of Revit usage per user to estimate peak and average demand.
   - **Cost Analysis**: Estimated the cost of Revit licenses per user session based on different usage frequencies.

## Results
- Identified the top users based on the frequency and duration of Revit usage.
- Calculated the minimum number of licenses required to meet demand, with recommendations based on usage patterns.
- Provided insights on the correlation between usage frequency and duration, aiding decision-making for license procurement.

## Key Visualizations
The analysis includes:

- Daily counts of unique users.
- Histograms and box plots showing the distribution of Revit usage frequencies among employees.
- Scatter plots highlighting the correlation between average daily usage duration and usage frequency.

## Next Steps
To improve the accuracy and relevance of these insights, the following steps are recommended:

- **Role Analysis**: Classify users by their roles (e.g., architect, engineer) to determine if usage patterns vary by role.
- **Project Stage Analysis**: Analyze usage by project stages (e.g., design, detailing) to account for changes in Revit needs over time.
- **Predictive Modeling**: Develop models to forecast hourly or daily license requirements based on historical trends.

This analysis provides actionable insights that can help the company make data-driven decisions regarding Revit license purchases, balancing cost with operational needs.
