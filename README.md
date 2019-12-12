## Introduction

Food security is a major public health concern. In order for people to live their healthiest lives, they must be able to access fresh produce. During my undergraduate studies, I worked part-time as a gardener and at a farmer’s market for two years, so food systems are of personal interest to me. During my time working these jobs, I learned about the way in which outside factors can largely influence an individual’s ability to access foods which are considered healthy. My hope is to observe what factors can predict the availability of various fruits and vegetables. Through this investigation, we may gain an understanding of what external forces are associated with the stability of our food systems and the health-related decisions that individuals are able to make.

One of the main priorities for this project is to create an interactive way to observe the trends of food availability over time, and how these metrics are associated with external factors. Such factors include real gross domestic product, diabetes prevalence, and unemployment rate. The ideal way to explore these trends would be through a Shiny app. In one tab, I will provide an interactive way to observe trends over time for a vegetable or fruit of choice, and in a second tab, I will provide an opportunity for the user to observe how availability correlates with other factors through scatterplots. Additionally, I hope to implement regression analyses to create a predictive system for food availability and consumption. 

### Data Sources

Data on per capita annual availability for fruits and vegetables is available through the US Department of Agriculture. Total availability, as well as values for fresh fruit, processed fruit, fresh vegetables, and processed vegetables were downlaoded and availability amounts from 1970 to 2016 were combined into one dataframe. Potential predictors included in the analysis were diabetes prevalence (available from the Centers for Disease Control and Prevention), average annual farm income (available from the US Department of Agriculture), annual unemployment rate (available from the US Department of Labor Statistics), percent GDP spending on healthcare (available from the Centers for Medicare and Medicaid Services) , average life expectancy, population, and GDP (available from the Gapminder foundation). Note that farm income is in terms of 2019 dollars (i.e. adjusted for inflation).

### Exploratory Data Analysis

To begin, I wanted to observe how the total availability varies over time.
