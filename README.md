# Life Expectancy Trends Worlwide

Completion date: August 18, 2023      

## Table of Contents
1. [Tableau Dashbord](#tableau-dashboard)
2. [Overview](#overview)
3. [Data Question](#data-question)
3. [Technologies Used](#technologies)
4. [Data Sources](#data-sources)
5. [Conclusion](#conclusion)

## Tableau Dashboard
Link: https://public.tableau.com/shared/JY7SX44YN?:display_count=n&:origin=viz_share_link

<a name="overview"></a>
## Overview
  This project dives into the intricate dynamics of life expectancy variations among diverse countries during the period from 2010 to 2015.  The investigation is fueled by a comprehensive analysis of key determinants encompassing smoking prevalence, alcohol consumption trends, and gross domestic product (GDP) indicators.  By meticulously dissecting these complex factors, the objective is to uncover the underlying correlations that have exerted influence on the fluctuations in life expectancy trends.  This exploration encompasses trends across all countries, while also considering distinctions between developed and developing nations. This approach allows us to gain a nuanced understanding of how various factors interact to shape life expectancy outcomes on a global scale, considering the diverse contexts of different types of countries.

<a name="dataquestion"></a>
## Data Question
  1. How does the interplay of alcohol consumption, smoking rates, and gross domestic product (GDP) correlate with the differences in life expectancy trends among developed, developing, and all countries from 2010 to 2015?
  2. Are there any correlations between alcohol consumption and smoking related mortalities compared to GDP?

<a name="technologies"></a>
## Technologies Used
1. Python / Pandas /Requests - for exploration, collection, cleansing, and aggregation of the dataset
2. Tableau - creating the final presentation, visuals, and ineractive dashboard

<a name="datasources"></a>
## Data Sources
To answer the question above, I used the following sources to collect the datasets used in my analysis: 

1. Life Expectancy Demographics - webscraped using the following website:
    https://www.macrotrends.net/
2. Smoking Rates (Factor #1)
    https://ourworldindata.org/grapher/death-rate-smoking
3. Consumption of Alcohol Rates (Factor #2)
    https://ourworldindata.org/alcohol-consumption
4. Developed/Developing Country and Gross Domestic Product (GDP) per Capita (Factor #3)
| | https://www.kaggle.com/datasets/amirhosseinmirzaie/countries-life-expectancy

<a name="conclusion"></a>
## Conclusion

  1) Consumption of Alcohol have a slight positive correlation to Life Expectancy
  2) Smoking Related Mortalities Rates has a positive correlation to Life Expectancy
  3) GDP per Captia has a positive correlation to Life Expectancy
  4) Both Consumption of Alcohol and Smoking Related Mortalites are more prevalent in the countries with lower GDP; however, those contributing factors do continue to follow the trend of increasing rates as GDP increases.