
# Kickstarting with Excel
Analysing Kickstarter Data on two different parameters.

## Overview of Project

This project uses the Kickstarter dataset to visualize campaign outcomes based on their launch dates and their funding goals. 

### Purpose

To find out different campaign outcomes of the play fever in relation to their launch dates and their funding goals using Excel.

## Analysis and Challenges

###### *Analysis*

* This Analysis is based on crowdfunding for the category Theater. The data being analysed is for crowdfunding outcomes- "successful", "failed" and "canceled" not including live campaigns. 
* The number of campaigns is further analyzed on the basis of different months of the year & on the crowdfunding goals.
* The data is visualized with the help of Pivot Tables & Pivot Charts.

###### *Challenges*

* The data available is from 2010 till 2017 for category "Theater" but the data is not evenly distributed over the years and is more concentrated on years 2014, 2015 & 2016.
* The data available is heavily focussed on campaigns in two countries with US having 65% share of the outcomes under the category "Theatre" followed by GB with a share of 26%.
* The campaign data is concentrated for campaign goals of up to $9999. There is some data for goals between 10000 to 24999. But for goals greater than 25000 there is limited campaign data.

### Analysis of Outcomes Based on Launch Date



* The line chart named Theater_outcomes_vs_Launch.png shows theater outcomes plotted against the months of the year.


![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/104603128/167521352-c42f9fb2-34f3-45f2-bb55-84a247f57269.png)

* The number of failed campaigns is high during the months of May, June, July  & October. 
* The number of successful campaigns is the highest in May followed by June & July.
* The delta between the number of successful and failed campaigns is highest in May followed by June & July.
* The delta between the number of successful and failed campaigns is the least in December. 

### Analysis of Outcomes Based on Goals


* Line chart named Outcome_vs_Goals.png shows relationship between goal-amount ranges on the x-axis and the percentage of successful,failed, or canceled projects on the y-axis.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/104603128/167521475-90fae8d4-1219-4726-97eb-bba616176b7b.png)

* For Goals upto 19999 the Percentage of Successful Campaigns is more than Percentage of Failed Campaigns.
* The percentage of Failed Campaigns peak at Goals between 45000 to 49999 followed by 25000 to 29999.
* The percentage of Successful Campaigns peak in goals less than 1000 followed by goals between 35000 to 44999.


### Challenges and Difficulties Encountered

* In line Graph Outcomes_vs_Goals, on the X axis goals ' less than 1000 ' label was apppearing after ' 50000 or more ' label on plotting the pivot chart from the pivot table because of which the graph displayed was different , this error was corrected by using Manual sorting.


## Results

1. *What are two conclusions you can draw about the Outcomes based on Launch Date?*

* The best month for campaigns is May followed by June & July.
* The percentage of failed campaigns out of all campaigns is the least in May. 

2. *What can you conclude about the Outcomes based on Goals?*

* The Percentage of Successful Goals is maximum for goals less than 1000 . 
* The Percentage of Successful Campaign goals is greater than the Percentage of Failed Campaign Goals except for Goals between 15000 to 34999 and for 45000 and more.

3. *What are some limitations of this dataset?*

* In case of Oucomes based on Goals more than 19999 the data is very limited.
* In this method, the conclusion is limited to X-Y model, hence unable to add multiple variables at the same time.

4. *What are some other possible tables and/or graphs that we could create?*

* Creating a pie chart to display percentage of outcomes in relation to countries in case of Outcomes based on Launch Date.
* Creating another pie chart to visulaize Percentage of Successful, Failed & Canceled w.r.t. the goal outcomes.
