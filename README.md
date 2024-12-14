# Healthcare-analytics-project
Built an interactive Tableau dashboards and story summarizing healthcare data insights, including diabetes trends, BMI distribution, and patient health metrics.

## Overview
This project analyzes a healthcare dataset containing information about patients aged 20+ with various health parameters, including blood pressure, BMI, glucose levels, insulin, and diabetes status. Using Tableau, the data is visualized through interactive dashboards and a story, providing insights into patient health trends and distributions.

## Objectives
1. Analyze and visualize key health metrics to understand patient trends.
2. Create interactive dashboards and a story for effective presentation of healthcare data.
3. Use calculated fields, custom shapes, and bins for enhanced visualizations.
4. Provide actionable insights on diabetes distribution, BMI categories, and blood pressure trends.

## Features
1. Dashboard 1: Healthcare Overview
- Includes a healthcare-related image.
- A meaningful title summarizes the dataset insights.
2. Dashboard 2: Healthcare Insights
- View 1: Diabetic vs. Non-diabetic Distribution
  A shape chart shows the percentage distribution of diabetic vs. non-diabetic patients.
  Tooltip displays patient count.
  Action filters enable interactivity.
- View 2: Patient Summary by Blood Pressure Category
  Shapes differentiate blood pressure categories and count of patients.
  Action filters enable interactivity.
- View 3: Histogram: BMI by Age Groups
  Histogram with bins of size 5 (e.g., 20–24, 25–29).
  Age group bins are aliased for clarity.
  Average BMI is displayed and colored using a red palette.
- View 4: Single Bar Chart: BMI Type Distribution
  Patients are classified into four BMI categories: Underweight, Healthy Weight, Overweight, Obese.
  Displays the percentage distribution of patients by BMI type.
  Action filters enable interactivity.
- View 5: Patient Breakdown by Blood Pressure and Diabetes
  Highlights diabetic patients with high and low blood pressure categories.
  Displays patient count for each combination.
- View 6: Heat Map: Health Factors by Age Group
  Heat map visualizes various health factors (e.g., glucose, insulin) segmented by age groups.
2. Story: Healthcare Summary Report
- Story Name: Healthcare
- Title: Healthcare Summary Report
- Description: Summarizes key insights into patient health data.
- Structure:
- Story Point 1: Dashboard 1 (Healthcare Overview)
- Story Point 2: Dashboard 2 (Healthcare Insights)
- Story Point 3: Heat Map Worksheet
- Layout: Navigator style with numbered navigation.
- Custom Size for optimal visualization.

## How to Use
1. Open the Healthcare_Analytics.twbx file in Tableau Desktop or Tableau Public.
2. Explore the dashboards and story to gain insights into patient health metrics.
3. Interact with the charts using filters and action-enabled visualizations.

## Instructions to Recreate
1. Connect to the Healthcare.xls dataset in Tableau.
2. Use an Extract connection for optimal performance.
3. Create calculated fields for:
- Diabetic vs. Non-diabetic classification.
- BMI categories.
- High and Low blood pressure categories.
- Build the following visualizations:
- Diabetic vs. Non-diabetic distribution.
- Patient summary by blood pressure.
- Histogram of BMI by age groups.
- BMI type distribution.
- Blood pressure and diabetes bar chart.
- Heat map of health factors by age group.
- Create two dashboards and a story with a custom layout, as outlined in the requirements.
