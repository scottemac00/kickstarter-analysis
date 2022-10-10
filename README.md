# Kickstarting with Excel

## Overview of Project
The data presented here illuminates how different theater play Kickstarter campaigns fared in relation to their launch dates and fudning goals. Campaign outcomes are visualized based on launch dates and funding goals.
### Purpose
Louise took previous analysis into consideration when she made her campaign for her last Kickstarter-funded play, *Fever.* Based on this, and *Fever* coming close to its fundraising goal in a short amount of time, she asked for additional data on how different campaigns fared in relation to their launch dates and their funding goals.
## Analysis and Challenges
For this analysis the data from the base Kickstarter tab of the Kickstarter Challenge excel workbook was filtered to meet Louise's requirements. The first step in curating the information for Louise was acknowledging her desired outcomes and creating a visualization that accurately depicted said outcomes.   
### Analysis of Outcomes Based on Launch Date
For this technical analysis I created a pivot table that displayed the quantity of successful, failed, and canceled outcomes by month over the entire theater play sample set. This data was then visualized with a graph that depicted the relationship of campaign outcome based on time of year. This pivot table may be adjusted to further refine data based on time of year (e.g., month / season / quarter), year (e.g., early 2000s to mid 2000s), and could also be focused on country of origin. 
### Analysis of Outcomes Based on Goals
This technical analysis required filtering and sorting the data to look at campaign funding goals, breaking them out by dollar amount, and correlating the success/failure/canceled percentage to the campaign funding goal. A new sheet in the workbook titled "Outcomes Based on Goals" was created and from there data pulled in from the main Kickstarter sheet to support the analysis and visualization.  
### Challenges and Difficulties Encountered
The biggest challenge was checking and re-checking my work to ensure both veracity and accuracy. I spent quite a bit of time relooking the analysis sheet for Outcomes based on Goals due to an error in the formula. Thankfully, examining my process enabled me to identify the error, check for redundancies in follow-on formulas, and correct all errors. 
Moving forward I would include a peer review prior to submitting data to customers for use. This is a common practice for quality control. I also now have an organizational process asset in this repository and on my computer for future reference.
## Results

- Two conclusions we can draw about the Outcomes based on Launch Date:
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/114544346/194963517-3ca44661-b728-49e6-a3c9-557c674dfc2e.png)

1. The most successful theater campaigns occur in the spring (April through June), while campaign failure tends to peak in May and October annually. This may be due to seasonal factors such as weather or available discretionary spending money.

2. Theater campaigns are seldom canceled. People love supporting the arts! 

- The Outcomes based on Goals analysis shows us that theater campaings with goals less than $5000 have best success rates and relatively low failure rates, with those campaigns between $35k and $45k, though significantly fewer in number, have slightly leower success and failure rates, respectively. It seems that if the producer keeps a goal below about $17k they will have the greatest chance for a successful campaign.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/114544346/194963524-3b989931-ba48-47cd-8e46-441fb926bbc2.png) 

- Some limitations of this dataset:
The dataset is limited in scope because it represents a relatively small amount of activity (4,115 campaigns) given the 9 year time range and global span of information. While it certainly represents a sample of Kickstarter campaign data from 2009 to 2017, it could be more directly correlated by region or country, despite Kickstarter being a global online fundraising platform. 

- Some other possible tables and/or graphs that we could create might more accurately key the customer or user in to the important part of the chart. Circling or highlight a particular data point, then correlating that information might more rapidly orient the user by taking out the 'interpolation' requirement. Further refining the data to better represent where Louise wants to produce her play, the time of year, and including some additional backer information (e.g., number, percent funded) might give her beter insight into her production decision.
