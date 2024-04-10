# [Public Health Dashboard Project Recreation](https://public.tableau.com/views/FluShotDashboard_17051720474710/Dashboard1?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link)

## Overview

This dashboard is a recreation of a project I undertook for a client during my freelance data specialist tenure, now utilising mock data for presentation purposes. It is designed to offer analytical insights and visualisations on the distribution of flu shots throughout 2022, focusing on coverage metrics by age, race, and county. The dashboard also tracks cumulative vaccination numbers, the total flu shots administered in 2022, and categorises patients based on their vaccination status.

## Tools and Technologies

- **SQL**: The primary tool for data extraction, transformation, and loading (ETL) processes, enabling detailed querying and manipulation of data within PostgreSQL databases.
- **Tableau**: Selected for its robust visualisation capabilities, allowing for the creation of a dynamic and informative dashboard to display the processed data.
- **PostgreSQL & pgAdmin**: Employed for the storage and management of mock patient data, facilitating the backend setup of the project.
- **Spreadsheet Software**: Used to analyse data extracted via SQL for desktop analysis, providing a versatile platform for viewing and manipulating data sets.
- **ODBC**: Utilised for establishing connections between the desktop version of Tableau and SQL databases, ensuring a seamless integration for direct querying and visualisation.

## Implementation Steps

### Database Setup and Mock Data Import

The project began with the creation of SQL tables designed to house patient demographics, flu vaccination records, and other pertinent data. Following this, mock data was carefully imported to simulate a real-world scenario for analysis, ensuring a foundation for the subsequent steps in the project.

### SQL Queries and Data Preparation

Custom SQL queries were crafted to extract and prepare the data according to the dashboard's specifications. These queries were essential for selecting relevant patient information by demographics and vaccination status and were sophisticated enough to join various data tables to filter for active patient records based on specific criteria.

### Dashboard Development in Tableau

The next phase involved the direct connection of Tableau to the prepared mock data sources, either through downloaded CSV files or direct database connections via ODBC. The dashboard was then developed to include:

- **Demographic Analysis**: Bar graphs and colour-coded maps showing flu shot coverage by age, race, and county to identify disparities and areas of success.
- **Patient Lists**: Detailed lists categorising patients by their vaccination status, enabling targeted health interventions.
- **Compliance Recognition**: Badges for regions or demographic groups reaching high vaccination compliance, encouraging public health engagement.
- **Vaccination Trends**: Graphs summarising vaccination efforts over time, aiding in the identification of trends and facilitating planning for future health campaigns.

## Project Insights

Recreating this dashboard with mock data allowed me to demonstrate the entire process of developing a data-driven health analytics tool, from data setup and querying with SQL to visualisation with Tableau. This project reflects my ability to handle complex data sets and transform them into actionable insights, showcasing flu vaccination trends and helping to identify areas for improvement in public health strategies.

## Conclusion

This project exemplifies the power of combining technical skills in SQL and Tableau to create meaningful public health dashboards. It highlights my comprehensive approach to data analysis and visualisation, demonstrating the ability to generate impactful insights that can guide public health decisions and strategies. The recreation of this dashboard serves as a testament to my expertise in leveraging data for meaningful outcomes.
