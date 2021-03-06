
# 911 Calls Data Analysis

## Objective: 
Using data analysis with Python on 911 Call Data sourced from Kaggle.

## What we can conclude from the graphs below:
From this Kaggle dataset, I found what locations (specifically, what zip codes and townships) had the most 911 Calls in Montgomery County, located in Pennsylvania. I also narrowed it down to the reasons for the 911 Calls (Fire, EMS, and Traffic) as well as the amount of calls received for each reason aforementioned. Then, I went ahead and separated those reasons by days of the week, along with the number of calls for each reason.

Next, I found the total number of 911 Calls per month and grouped the aggregate calls by month to see their fluctuations throughout time and also separated the calls by reasons. Lastly, there are two heat maps and two cluster maps which shows 911 Call activity per hour for each day of the week and comparing the day of the week alongside the month, respectively.

The main reasons for calling into 911 seemed to be both EMS and traffic. When diving into these reasons a bit more, I separated the reasons by days of the week and found that overall, EMS calls remain steady throughout the week, as does fire. However, traffic seems to take a dip during the weekend (Saturday and Sunday). I suspect that this could be due to the Monday through Friday work week, school traffic, etc. 

.....


### Findings
 
- Top 5 zip codes for 911 Calls
    1.	19401
    2.	19464
    3.	19403
    4.	19446
    5.	19406

- Top 5 townships for 911 Calls
    1.	Lower Merion
    2.	Abington
    3.	Norristown
    4.	Upper Merion
    5.	Cheltenham

- Type of reasons for 911 calls and their respective counts

![Alt text](/graphs/reasoncount.png?raw=true)

- Separating reasons by days of the week, as well as their respective counts

![Alt text](/graphs/dayofweekcount.png?raw=true)

- Total number of 911 Calls per month

![Alt text](/graphs/callspermonth.png?raw=true)

- Grouping aggregate calls by month to see fluctuations throughout time

![Alt text](/graphs/aggcallsmonth.png?raw=true)

- Separating 911 calls by reason (EMS, Fire, and Traffic)

![Alt text](/graphs/ems.png?raw=true)

![Alt text](/graphs/fire.png?raw=true)

![Alt text](/graphs/traffic.png?raw=true)

- Heat Map and Cluster Map showing 911 Call Activity per hour each day of the week

![Alt text](/graphs/heatmap.png?raw=true)

![Alt text](/graphs/clustermap.png?raw=true)

- Heat Map and Cluster Map comparing day of the week against the month

![Alt text](/graphs/heatmap2.png?raw=true)

![Alt text](/graphs/clustermap2.png?raw=true)


