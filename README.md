# Kickstarting with Excel

## Overview of Project
Kickstarter is a powerful platform that allows people to launch their start-ups with the help of donations from the strangers (i.e., pledgers). In past, Kickstarter has been used to fund campaigns ranging from video games and short movies to food restaurants and theater performances. The current analysis is performed to help our client investigate the trends in previously executed theater campaigns to determine the most favourable conditions for a successful kickstarter launch.
### Purpose
The goal is to establish the trends in the theater-related Kickstarter environment: whether the predetermined monetary goals and the time when the Kickstarters are introduced have an effect on the chances of successful outcomes for said projects. Over 4000 various previosly lauched Kickstarter campaigns have been analyzed to investigate these trends of interest.
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/99566803/157083064-dcf6fbf9-af52-489d-ad9b-c57fecd033dd.png)
The Kickstarter data was examined in relation to campaign successes across various months throughout the year. As can be seen on the associated graph ("Theater Outcomes Based on Launch Date"), theater performance Kickstarters were most successful if they were launched in or around the month of May (with May itself amounting to almost 110 successful launches). Contrary, the least favourable months to launch a theater Kickstarter seems to be around the New Year - both in December and January, with December specifically having an equal amount of successful and failed campaigns, suggesting it might be a risky move to start a campaign during this time.

### Analysis of Outcomes Based on Goals
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/99566803/157083080-f034b1f6-ff13-4e2a-b063-df8f1be3b433.png)
Additionally, the success of previously launched theater Kickstarters was examined in relation to the predetermined monetary campaign goals. The data (which can be seen in "Outcome Based on Goal" graph) suggests that there is a fairly steady trend for campaigns to have a higher failure rate with higher monetary goals. As such, for instance, none of the campaigns in the 45000 to 50000$ range were successful in their completion. Correspondigly, the highest number of succesful campaigns was associated with lower pledging goals, with Kickstarters asking for less than 1000$ in donations seeing an almost 80% success rate of completion.

### Challenges and Difficulties Encountered
One potential flaw with the Outcomes based on Launch Date analysis is that the baseline for canceled Kickstarters was pretty much non-existent, making it hard to examine whether some less successful months could be attributed to outright failure or the projects or their withdrawal from the campaigns. Addituionally, only a chunk of Kickstarter campaigns was examined, leaving it an open possibility for the overall data to represent a somewhat different story in terms of succesful trends.

One problem that arises in regards to the Outcomes Based on Goals analysis is the unpredictable behaviour of the overall trend around the pledging goal of 35000 to 44999$, in which the data shows a sudden increase in successfully funded campaigns versus the failed ones. This data is partially challenging to interpret as it only includes a couple of data points, as opposed to the majority of the analysis, which might have caused such a fluke. However, further investigation is required with a bigger dataset in order to establish a stable trend for the above-mentioned monetary campaign goals.

## Results
To sum up the analysis, two points can be taken away from the Outcomes based on Launch Date data. First is that one might consider May as their launch month if they are seeking to secure the chances of a successful Kickstarter (followed closely by the month of June). Second, with the same idea in mind, a person trying to establish a successful theatre Kickstarter should avoid launching their campaign in the months of December and January, as they are seen as having the lowest success rate among the examined months.

For the Outcomes based on Goals data, the main takeaway is that the less money a campaign is trying to raise, the bigger the chances that such a campaign would be funded in full. As such, aiming for a lower to medium-sized pledging goal should be considered optimal.

One should keep in mind, however, that the current dataset is severely limited: the amount of campaigns examined is far less significant than the actuality of Kickstarter campaigns' load, the dataset only represents a span of three consequtive years between 2014 and 2016, making it somewhat outdated, and it excluded any live campaigns that are still currently undergoing the funding process. Further expanding the dataset would be beneficial for future analysis of the data, and interested parties might find it optimal to examine other factors, such as the estimated campaign lenght, the extend of the projects themselves (how big or small they might be), or the amount of pledgers supporting various causes to facilitate their Kickstarter campaign decisions.
