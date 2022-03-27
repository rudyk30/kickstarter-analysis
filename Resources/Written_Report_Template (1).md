# Kickstarting with Excel

## Overview of Project
Louise recently launched her Kickstarter campaign for her play, Fever, which nearly hit its fundraising goal in a short amount of time. This project was done to help Louise easily see how other campaigns fared in terms of their outcomes based on the campaigns funding goals and launch dates. To perform this analysis, the data was focused specifically on 3 outcomes: Successful, Canceled and Failed. In addition, the data was solely analyzing the Theater Parent Category and the Plays subcategroy as that is what Louise was primarily interested in. 
### Purpose
The purpose of this analysis was to analzyse the Kickstarter data set to allow Louise to visually understand how different campaigns performed based on their funding goals and launch dates. Using the findings from this analysis, Louise should be able to make better decsions on what time periods and funding goal ranges are ideal for a Kickstarter campaign for any future project she has. 
## Analysis and Challenges
The first part of the analysis was to visualize campaign outcomes based on launch date. This chart is specifically focusing on the Theater parent category as that is the parent category Louise wants to understand better in this portion of the analysis. The best way to represent this was to first extract the Year from the "Date Created Conversion" column, create a picot table and then make a Line Graph. 

-put graph here

This graph clearly depicts how Theater campaigns fared according to the month they were launched. Louise can clearly see trends in this graph to help her understand which months were more likely to yield a successful, failed or canceled campaign. 

The second part of the analysis was to visualize the percentage of successful, failed, and canceled plays based on the funding goal amount. To perform this analysis, ranges of funding goals were first created:

-put ranges image here

After setting the goal parameters, the Countifs formula was utilized to calculate the total number of projects that were successful, canceled or failed. Then, the Sum formula was used to calculate the total amount of successful, failed and canceled projects for each row. Following that, the percentage of plays that were successful, failed or canceled for each row. The best way to visualize this was by creating a line graph.

-put graph here

Louise can now clearly see how funding goals impact a Plays outcome. Through this graph she can now make more informed decsions on future funding goals for her projects as she can easily see which goal ranges yield the most failed outcomes. 


### Analysis of Outcomes Based on Launch Date

May is the month with the most successful, failed and total campaigns. Very few campaigns were canceled outright as only 37 out of 1369 projects were canceled. In addition, April was the month in which succesful campaigns started to increase, with the peak in May but a sharp drop from June to September. There was a 56% increase in succesful campaigns between April and May and a 41% decline in succesful campaigns between June and September. 

### Analysis of Outcomes Based on Goals

The most number of total projects for Plays had a funding goal between 1000 and 4999 and the most number of total projects that failed had a funding goal between 1000 and 4999 as well. However, taking a deeper look at the percentage of the total, the data tells a different story. This funding goal actually had the second highest Percentage succesful projects. 

### Challenges and Difficulties Encountered

While performing this challenge, the main challenge I encountered was inputting the Countifs formula due to the fact I'd never used it before. My main issue was understanding what the formula was calculating and what data I needed to input. The way I overcame these challenges was by utilizing Excel Help and watching a tutorial video on Youtube. After using those troubleshooting techniques, my formula was working and I understood what it was calculating. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

The colder months are less likely to yield a succesful outcome as there are significantly less succesful projects in these months wheh compared to the warnmer Summer and Spring months. We can conclude the best months to start a kickstarter campaign are the warmer late spring and summer months. 

- What can you conclude about the Outcomes based on Goals?

The funding goal that will most likely yield a succesful outcome is less than 1000 as it has a 76% success rate. The midpoint of the data is funding range between 15000 and 19999, following that the percentage failed increases drastically and the percentage succesful decreases. We can conclude that projects with funding ranges that are outside of the 15000 to 19999 goal range are more likely to fail. We can also conclude projects with a lower funding goal are more likely to succeed. 

- What are some limitations of this dataset?

One limitation of the dataset is the length of time we are analyzing. The report containts projects from 2009 to 2017 but there may be more data availaible as it is now 2022 therefore we are not working with more recent data. Another limitation is the dataset doesn't include project length or runtime. It may allow us to go even deeper in our analysis and asnwer questions to help Louise such as: "Are shorter projects more likely to be succesful?".

- What are some other possible tables and/or graphs that we could create?

A Bar chart could have been created to compare the outcomes of specific categories. A Box and Whisker chart could have also been made to understand potential outliers in the data and get a better view of the distribution of the dataset. 
