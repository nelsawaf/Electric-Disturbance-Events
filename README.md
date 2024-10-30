  # Electric-Disturbance-Events
  Electric Disturbance Events data analysis in north America in different regions for 22 years
  
  📑 Overview
  This project analyzes electricity outages across NERC (North American Electric Reliability Corporation) regions. Using Power BI for data visualization and analysis, the project explores patterns, event types, customer impact, and demand loss. The insights provide a comprehensive understanding of power outages across regions over time.
  
  🔍 Project Goals
  Analyze the frequency and types of power outage events.
  Measure the impact of outages on customers affected and demand loss (MW).
  Visualize outage data to identify trends and region-specific patterns.
  Provide insights that can help with forecasting and risk mitigation.
  
  🗂️ Data Structure
  Tables Used:
  •	Fact Table (fData):
  This table contains essential columns such as:
  o	Event Began
  o	Restoration
  o	NERC Region
  o	Event Type
  o	Demand Loss (MW)
  o	Number of Customers Affected
  
  •	Dimension Tables:
  o	dEvent: A table that provides details about different types of events and a conditional column for event categorization.
  o	dNERC: A dimension table listing NERC regions.
  o	dCalender: A dimension table listing dates.
  
  
  ⚙️Data Cleaning and Transformation
  The data was cleaned using Power Query to ensure consistency and accuracy. Key steps included:
  
  Handling missing data and inconsistencies in event records.
  Normalizing multiple NERC regions (e.g., "SERC, MECO") into a standard "multiple" category.
  Creating calculated columns such as totalDays and totalHours to better analyze event durations.
  
  
  🛠️ Tools Used
  Power BI: Data visualization and dashboard creation.
  Power Query: Data cleaning and transformation.
  Excel: Initial data preparation and validation.
  
  🚀 How to Run the Project
  Download the project files from this repository.
  Open the Power BI .pbix file.
  Ensure all data sources are correctly linked (fact and dimension tables).
  Explore the dashboards interactively using the provided filters.
  
  
  💡 Insights and Key Findings
  Certain NERC regions experience more frequent outages, particularly during specific seasons.
  Longer outages tend to have a higher customer impact in certain regions.
  Demand loss trends vary significantly across regions, highlighting the importance of localized response strategies.
  
  📈 Future Improvements
  Automating data updates through Power BI Service.
  Integrating external weather data to analyze environmental impacts on outages.
  Adding predictive models for forecasting future outages.
