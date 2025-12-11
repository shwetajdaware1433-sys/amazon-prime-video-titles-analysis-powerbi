# Amazon Prime Video Titles Analysis using PowerBi
## Table of Contents
- [Project Overview](#project-overview)
- [Obejectives](#objectives)
- [Process](#process)
- [Visualization](#visualization)
- [Insights Generation](#insights-generation)
- [Tools](#tools)
- [Challenges and solutions](#challenges-and-solutions)
  
### Project Overview
This project provides an end-to-end data analysis of Amazon Prime Video content, including Movies and TV Shows.
The goal is to uncover insights related to content distribution, ratings, genres, directors, and release trends.
Power BI is used to build an interactive and dynamic dashboard for better decision-making.

### Objectives

- To visualize Amazon Prime Video’s content library using Power BI.
- To provide insights into the number of titles, ratings, genres, and directors.
- To analyze trends in releases over time and across geographies.
- To enable better understanding of audience preferences and content distribution.
  
### Process  

- Data Collection : Collected Amazon Prime Video dataset containing details such as Title name, Genre, Director, Ratings, Type (Movie/TV    Show)
- Data Cleaning
   - Removed duplicates and irrelevant columns.
   - Standardized genre, director, and title names.
   - Handled missing values in ratings, release dates, or directors.
   - Used Power Query Editor in PowerBI
### Visualization

   - Connected Cleaned dataset to PowerBI
   - Created KPI cards for:
      1. Total Titles
      2. Total Ratings
      3. Total Genres
      4. Total Directors
      5. Start Date & End Date
   - Built interactive visualizations:
      1. Map visualization showing total shows by region.
      2. Ratings by total shows (bar chart / scatter plot).
      3. Total shows by release year (line chart).
      4. Genre-wise total shows (treemap / stacked bar chart).
      5. Movies vs TV shows breakdown (donut chart / column chart).

### Insights Generation

   - Analyzed visualizations to extract meaningful insights:
   - Most popular genres.
   - Release trends over years.
   - Distribution of content geographically.
   - Content type popularity (Movies vs TV Shows). 

### Tools

   - Power BI : Dashboard and Visualization

### Challenges and Solutions

  - Missing or Incomplete Data
    
     Solution: Handled missing values using Power Query (filled defaults, removed incomplete rows, or aggregated data).
  - Inconsistent Data Formats
    
     Solution: Standardized dates, genres, and names using Power Query transformations.
  - Generating Meaningful Insights
    
     Solution: Created KPIs, trend charts, and interactive slicers to highlight patterns and top genres.    

### Future Improvements

  - Add sentiment analysis from reviews.
  - Compare Amazon Prime Video with other streaming platforms.
