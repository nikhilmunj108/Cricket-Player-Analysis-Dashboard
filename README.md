# Cricket Player Analysis Dashboard - Power BI Project

## Overview
This project is a cricket player performance analysis dashboard built using **Power BI**. The dashboard allows users to explore key metrics such as batting average, strike rate, and bowling economy for various players, helping visualize and compare performance across multiple categories. This project was inspired by Dhaval Patel and Hemanand Vadivel from CodeBasics.

## Data Source
The data was scraped from the **ESPN Cricinfo** website using the **BrightData WebCrawler**. The dataset includes various cricket player statistics, which were cleaned and transformed using **Python** for efficient data modeling and visualization.

## Key Features
- **Dynamic Filtering**: Users can select players and view detailed analysis of their performance.
- **Performance Comparison**: Side-by-side comparison of players across multiple metrics like batting average, strike rate, and boundaries.
- **Advanced DAX Functions**: Utilized functions like `IF`, `ISFILTERED`, and `SWITCH` to create dynamic charts and interactive visuals.

## Data Pipeline
1. **Data Scraping**: 
   - Scraped cricket player statistics using **BrightData WebCrawler** from ESPN Cricinfo.
   
2. **Data Cleaning (Python)**: 
   - Cleaned the raw data using Python libraries like **Pandas** and **NumPy**. This included handling missing values, transforming data types, and formatting for Power BI ingestion.

3. **Power BI Data Modeling & Dashboard**:
   - Built relationships and calculated fields within Power BI to prepare the data for visualization.
   - Created multiple dashboards focused on different player categories (e.g., Power Hitters, Anchors, Finishers).
   - Visualizations include player comparison charts, batting average over time, strike rate analysis, and custom batting order.

## Python Libraries Used
- **Pandas**: For data manipulation and cleaning.
- **NumPy**: For numeric operations.
- **Matplotlib/Seaborn**: For any potential exploratory data analysis (EDA) before using Power BI.
  
## Power BI Features
- **DAX Functions**:
   - `IF`: For creating conditional columns based on player stats.
   - `ISFILTERED`: To adjust visuals dynamically when filters are applied.
   - `SWITCH`: For dynamically updating visuals based on selection.
- **Dynamic Charts**: Users can interact with visuals to drill down into individual player stats or view combined performance metrics.
- **Custom Formatting**: Used Power BI’s formatting features to create a clean and interactive user experience, such as dynamic titles and chart labels.

## Dashboard Insights
The dashboard provides key insights into player performance:
- **Power Hitters**: Visualize players with high strike rates and boundary percentages.
- **Anchors**: Understand how players contribute as steady scorers.
- **Finishers**: Identify players who perform under pressure at the end of the innings.
- **All-Rounders & Bowlers**: Analyze performance metrics for bowling economy, average, and strike rate.

## Installation and Usage
To run the project:
1. **Python Setup**:
   - Install the required libraries: `pandas`, `numpy` etc.
   - Run the Python script to clean and process the data.
   
2. **Power BI**:
   - Open the `.pbix` file in Power BI Desktop.
   - Explore the interactive visuals by selecting players, teams, and performance metrics.
   
## Challenges and Learnings
- **Data Scraping**: Scraping real-time sports data presented challenges, especially in terms of managing dynamic content.
- **Data Modeling**: Cleaning and structuring large amounts of data for efficient loading and visualization required careful handling of relationships and calculations.
- **DAX Mastery**: Gaining proficiency in advanced DAX functions like `IF`, `ISFILTERED`, and `SWITCH` allowed for creating highly interactive and dynamic reports.

## Future Enhancements
- **Real-time Updates**: Integrating APIs to pull live cricket stats directly into the dashboard.
- **More Detailed Analysis**: Adding player-specific performance under various conditions (e.g., venue, opposition).
