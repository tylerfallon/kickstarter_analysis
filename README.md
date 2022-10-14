# Kickstarting with Excel

## Overview of Project

Louise has been working on a Kickstarter campaign to raise funds and wants to determine when the best time to launch her campaign would be and what an appropriate monetary goal would be based on the outcomes of previous campaigns, which she has collected a large amount of data on. 

### Purpose

The purpose of this project is to create a visualization of the Kickstarter dataset in order to show various campaign outcomes based on their launch dates and funding goals. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

![OutcomesByLaunchDate](https://github.com/tylerfallon/kickstarter_analysis/blob/main/resources/Theater_Outcomes_vs_Launch.png?raw=true)

This chart shows the various campaign outcomes by month, which are taken from a pivot table that is filtered by category and launch date. It portrays the number of successful, failed, and canceled campaigns in a given month using color-coded lines so that the various outcomes can be easily compared. 

### Analysis of Outcomes Based on Goals

![OutcomesVsGoals](https://github.com/tylerfallon/kickstarter_analysis/blob/main/resources/Outcomes_vs_Goals.png?raw=true)

This chart shows the various campaign outcomes based on the Goal Monetary Range. The possible outcomes for campaign- successful, failed, and cancelled- were plotted with the y-axis showing the percentage of campaigns with each outcome and the x-axis showing the different monetary ranges for each campaign. When creating the table for the data, to retrieve the count of each outcome, the COUNTIF statement was used. 

### Challenges and Difficulties Encountered

When creating charts from our datasets, small bugs in the code used to derive certain data resulted in the chart data being incorrect, and thus charts that displayed the wrong correlations between data. When this occurred, I then had to go back into our datasets and go through the code in search for any potential bugs that could be skewing the data. As I learned new ways of charting and plotting data, I occasionally came across a few things I had done previously that could be optimized and refined using the new knowledge I had just acquired. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

From the line chart, it can be seen that May is the best month in which to start a campaign, as it produces the highest number of successful outcomes. In addition, December appears to be the worst month to launch a theater campaign, as it has the lowest number of successful outcomes. The number of failed and canceled campaigns are also relatively consistent across each month while there is a clear favor of the summer months (May through July) as the best time to start a campaign. 

- What can you conclude about the Outcomes based on Goals?

It can clearly be seen that play campaigns with higher goal monetary ranges have a higher percentage chance of failing. There is a clear trend downwards of campaign success as the goal amount becomes larger and larger. 

- What are some limitations of this dataset?

There are many other potential factors that can affect a campaign besides launch date, such as number of backers, various subcategories, and others. By only taking into account these few factors, the dataset is limited in that there are potentially other factors that can affect the outcome rate of a campaign by much more. 

- What are some other possible tables and/or graphs that we could create?

We could take into account the subcategories that we wish to target, number of backers, and average donation, and overlay this data onto our current graphs- then analyze the correlation between these various categories and the outcomes they may lead to for campaigns within our subcategory. 
