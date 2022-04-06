# Module 13 Challenge

---
## Citi Bike NYC Bikesharing Analysis
---

### Project Overview
Last summer you and your friend, Kate took a 2 week trip to NYC and experienced how useful the bikesharing options were to tourists and New Yorkers alike. You start thinking about starting a bikesharking service in your hometown, Des Moines, IA. Kate finds a potential angel investor to provide seed money for your venture. You need to research how the bike share industry operates in New York, and then make a proposal on how it might work in Des Moines. The purpose for the project is to analyze and visualize the data in order to build convincing evidence that the new bike-sharing program is a solid business venture.

### Challenge Objectives
Continue to develop your analysis and visualizations by completing the following:
- Change the trip duration column of the dataset to a datetime format
- Create 5 specific visualizations to share in your pitch:
    - Line Graph: "Checkout Times for Users"
    - Line Graph: "Checkout Times by Gender"
    - Heatmap: "Trips by Weekday per Hour"
    - Heatmap: "Trips by Gender (Weekday per Hour)"
    - Heatmap: "User Trips by Gender by Weekday"
- Create a Tableau story and write a report for the investor presentation

### Resources
**Data Sources**
- 201908-citibike-tripdata.csv

**Software**
- Jupyter Notebook 6.4.5
- Pandas library
- Tableau Public 2021.4
- Visual Studio Code 1.63.2

### Challenge Results
Below are screenshots of my Tableau story analysis, which is linked [here](https://public.tableau.com/views/NYCCitiBikeAugustAnalysis_16492034190480/NYCCitiBikeAugustAnalysis?:language=en-US&:display_count=n&:origin=viz_share_link).
## NYC Citi Bike Analysis Screenshots: 

NYC City Bike Starting Locations: Grouping of all trip starting locations
![](https://github.com/saraegregg/Mod14_Bikesharing/blob/main/images/story_p1.png)

Customer Type: 2.3 million rides in the month of August 2019 with 81% of riders using subscription
![](https://github.com/saraegregg/Mod14_Bikesharing/blob/main/images/story_p2.png)

Highest traffic hours are from four pm through 7 pm
![](https://github.com/saraegregg/Mod14_Bikesharing/blob/main/images/story_p3.png)

The length of Citi Bike rentals
![](https://github.com/saraegregg/Mod14_Bikesharing/blob/main/images/story_p4.png)

The length of Citi Bike rentals by gender
![](https://github.com/saraegregg/Mod14_Bikesharing/blob/main/images/story_p5.png)

Peak bike usage by weekday hour
![](https://github.com/saraegregg/Mod14_Bikesharing/blob/main/images/story_p6.png)

Peak bike usage by weekday hour and by gender
![](https://github.com/saraegregg/Mod14_Bikesharing/blob/main/images/story_p7.png)

Bike usage by weekday and by gender, grouped by subscriber and single users
![](https://github.com/saraegregg/Mod14_Bikesharing/blob/main/images/story_p8.png)

## Summary
Main take-aways from this analysis are:
     - most riders are male, 
     - most of the riders use a subscription and rent Citi Bikes during the weekday,
     - most of the usage occurs in the morning hours and late afternoon,
     - male and female gender groups' usage and trip durations are similar,
     - most of the trips have a short duration of about 5-6 minutes.

I would recommend that analysis of subscription rates among the gender groups to better understand the groups of people that most use the Citi Bike service in New York City, as well as similar analysis of different months to determine trends across the year. It would be interesting to expand the dataset to determine if there is a correlation between the weather and the ridership and to answer the questions: does bike usage by subscribers for commuting drop darastically in the winter months or in inclement weather? Could a bikesharing company in Iowa be profitable yearround?