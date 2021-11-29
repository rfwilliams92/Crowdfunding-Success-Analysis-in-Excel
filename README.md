# Kickstarting with Excel

## Overview of Project

Analysis of fundraising goals and launch dates of theater fundraising campaigns. The data set consisted of 4115 fundraising campaigns from 2014 to 2016.

### Purpose

Find the optimal time, calendar month, to launch a fundraising campaign for a theater production and optimize fundraising goal.

## Analysis and Challenges

Analysis of the 4115 fundraising campaigns was done using Excel. I used pivot tables, and other analytical functions to create a clear graphs to show the optimal month for launching a campaign and optimal fundraising goals.

### Analysis of Outcomes Based on Launch Date

Using a pivot table to sort the data sets and create a line graph, I was able to show that May is the optimal month to launch a fundraising campaign for theater productions. The Line Graph, Theater_Outcomes_vs_Launch.png, shows the number of successful, failed, and canceled campaigns for each month over a calendar year.

### Analysis of Outcomes Based on Goals

A fundraising goal of $1-$4999 shows to be the most successful when analyzing percentage successful vs percentage failed. I found these percentages using COUNTIFS functions to separate successful campaigns from failed campaigns and further segment them into a small categorical fundraising goal ranges.

### Challenges and Difficulties Encountered
Using the COUNTIFS function cell by cell can lead to errors in the analysis. Also the formatting of data types can wreak havoc on operations and cell functions. Specifically the YEAR() function column had to be set to “general” formatting, rather than “date” vs the launch_date column had to be set to “date” otherwise it would produce non-sensical data.

## Results

We can determine that May is the best month to launch a fundraising campaign for theater productions by looking at the Theater_Outcomes_vs_Launch.png line graph. May had the largest number of successful campaigns, 111 campaigns, and also shows that it had the largest percentage of successful campaigns 111 (successful campaigns) / 166 (total number of campaigns in May) or a 66.9% success rate.

The line graph Theater_Outcomes_vs_Launch.png also shows that the 2 months immediately following May also have a larger number of successful campaigns than that of the other 9 months of the year. If the Month of May is not feasible for some reason, the summer months prove to be the better months to launch a fundraising campaign for a theater production.

For a theater production, a fundraising goal of $1-$4999 is the most successful for a theater production, as seen in Outcomes_vs_Goals.png. The percentage successful trends downward as the fundraising goal increases with an exception of $35000-45000. Although this shows an exception the general trend, the data set is so small we must limit the validity of the percentages.

Further analysis could be done the number of backers and average donation for successful campaigns for theater production. A pivot table could easily be implemented to show trends. This could provide insights for marketing/campaigning.
