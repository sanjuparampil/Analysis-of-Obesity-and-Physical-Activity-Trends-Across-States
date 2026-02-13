# Analysis-of-Obesity-and-Physical-Activity-Trends-Across-States
This mini project focuses on analysing obesity and physical activity trends across different states over multiple years using public health data. The objective of the project is to clean and prepare the dataset using Excel and Power Query, and then build an interactive dashboard using Power BI to identify trends, regional differences, and gender-based variations in health indicators. The project aims to transform raw data into meaningful insights that support data-driven understanding of public health patterns.

# Tools Used
Microsoft Excel and Power BI 

# Data Cleaning and Preparation (Excel & Power Query)
   -  Imported the raw dataset into Microsoft Excel and converted it into a structured table with headers.
   - 	Used Power Query Editor in Excel to:
       - Rename columns for better clarity (LocationDesc as State, Data_Value as Value)
       - Set appropriate data types for numeric and text fields
       - Remove rows with missing or null values in the Sex and Value columns
       - Filter the Class to relevant indicator categories such as Obesity and Physical Activity
       - Filter gender values to include only Male and Female
       - Remove duplicate records to ensure data consistency
       - Finalized a clean and analysis-ready dataset for visualization.

# Data Visualization and Dashboard Creation (Power BI)
  - Imported the cleaned dataset from Excel into Power BI Desktop for visualization and analysis.
  - Created calculated measures in Power BI to support analysis:
    - Average Value
    - Maximum Value
    - Minimum Value
    - State Count
  - Designed an interactive dashboard using multiple visualizations:
    - KPI cards to display overall metrics such as average value, maximum value, minimum value, and number of states
    - Line chart to analyze trends in obesity and physical activity over time
    - Bar charts to compare obesity and physical activity levels across different states
    - Line chart to compare male and female obesity trends over the years
    - Table visual to display detailed data for reference and validation
  - Added slicers to enable interactive filtering by:
    - Year
    - State
    - Indicator Category (Class)
    - Gender
  - Applied formatting and styling to improve readability and visual appeal:
    - Used a consistent color theme
    - Adjusted visual alignment and spacing
    - Added titles and labels for clarity
    - Designed a clean, single-page dashboard layout
  - Interpreted trends and patterns from the dashboard to derive meaningful insights related to obesity and physical activity across states.

# Key Insights 
   - Obesity levels show a gradual increasing trend across many states over the years.
   - Certain states consistently report higher obesity levels compared to others.
   - Physical activity levels vary significantly across regions, indicating lifestyle differences.
   - Male obesity rates are slightly higher than female rates in most years.
   - Recent years show a noticeable rise in obesity levels, highlighting growing public health concerns.



