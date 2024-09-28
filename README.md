# Road-Accident-Report-Accident Data Analysis Dashboard
Overview

This project involves analyzing accident data from the years 2021 and 2022. The goal is to create a comprehensive dashboard using WPS Office Spreadsheet that provides insights into various aspects of the accidents, including casualties, accident severity, vehicle types, road types, and more.

Problem Statement:

Build an comprehensive Road Accident Dashboard for 2021 and 2022 to gain actionable insights on:

- Primary KPI: Total Casualties post-accident - Key Metrics: Casualties & percentage by severity, vehicle

Type with maximum casualties

- Secondary Metrics: Casualties by vehicle type, monthly trends, road type impact, road surface distribution, and location-based analysis

Stakeholders Involved:

Ministry of Transport, Road Transport Department, Police Force, Emergency Services, Road Safety Corps, Transport Operators, Traffic Management Agencies, Public, Media

Meta Data:

- File Type: .xlsx

- Rows: 3.07 Million

- Fields: 21

Source: Kaggle Dataset 

1.Understanding Data:

Analyzed a large Excel file containing 3.07 million rows and 21 fields.

2.Data Cleaning:

Applying Filters: Used Excel filters to identify and correct errors, missing values, and inconsistencies.

Ensuring Data Integrity: Verified that unique identifiers (e.g., accident index) were complete and not duplicated. Correcting Errors: Fixed typos and inconsistencies (e.g., corrected 'fetal' to 'fatal').

3.Data Preprocessing:

Creating New Columns: Added 'Month' and 'Year' columns to facilitate time-based analysis.

Extracting Values: Used Excel functions (e.g., `=TEXT() function) to extract and format month and year from accident dates.

4. Adjusting Calculations and Charts:

Percentage Calculation: Computed percentages of casualties for different severity levels (e.g., Serious, Fatal) by dividing individual totals by the overall number of casualties.

Creating Charts: Developed and formatted donut charts to visualize severity data.

5. Integrating Data into Dashboard:

Incorporating KPI Values: Extracted key performance indicators (KPIs) from pivot tables and ensured their accuracy.

- Formatting KPIs: Added KPIs to the dashboard, adjusting font sizes, colors, and placement for improved readability and visual appeal.

6. Finalizing Dashboard:

- Objective: Complete the dashboard design for user-friendly interaction and presentation.

- Design Cohesion: Ensured all elements of the dashboard were well-integrated and visually appealing.

- Note: This is not a dynamic dashboard because I’m using the WPS basic version, which does not support slicers or the timeline feature.
