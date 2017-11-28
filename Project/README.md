# How to Make or Break a Country

Over the last couple of decades the number of nations on our planet has fluctuated considerably, from 167 widely recognized sovereign states in the 1970s to 195 in this decade. While some nations have unified, the noticeable rise in the number of countries is a product of the separation of pre-existing states.

There have been a number of volatile fractionalizations in the last few decades. The effects of such hostilities are far reaching and linger on for decades. These repercussions can be felt long after a supposed resolution has been achieved. As such, gaining a better insight into the events that could potentially detect future conflicts of this kind, and their peaceful mediation, before the fact, is a topic of great interest to us.

This project aims to explore the possible similarities and differences in the events preceding both violent unilateral declarations of independence and conflictless dissolutions of nations. We hope to be able to apply our findings to current world events and provide an early indicator of potential future unrest.


# Research questions
These are the preliminary research questions, which are subject to change during the subsequent stages of the project.

 - Is it possible to detect differences in the patterns of socio-political behaviour that precede both violet unilateral and nonviolent declarations of independence?

 - Do unilateral declarations of independence have similar or diverging preceding paths?

 - Are there recognizable patterns of behaviour that occur in the current independence movements across the globe (e.g. Catalonia, Scotland…)?



# Dataset
The primary dataset that we will use in this project is GDELT - The Global Database of Events, Language, and Tone. This dataset comes in two versions - 1.0 and 2.0:
- The GDELT 1.0 database contains information about newsworthy events that occurred from January 1st, 1979. until the present day. From January 1979 through the end of March 2013, records are stored in monthly and yearly files by the date the event took place. Beginning with April 2013, files are created daily, which provides a huge amount of historical data for our analysis. Also beginning with April 1st 2013. each reported event contains the URL of the news source that reported it.
- GDELT 2.0 database records start from February 19th 2015 and are updated every 15 minutes. In addition to the higher number of events, this database also adds media mentions of the specific event that occurred, which can be used to track the discussion about that event in time. Also, this database adds more detailed sentiment analysis to every event and increases the volume of data coming from the Non-Western world, which will also be important in our analysis.

Each entry in the dataset contains, among other things, an exhaustive description of the two primary actors which are participating in the event, it's date and location, as well as information about the type of the specified event. This type is the CAMEO (Conflict and Mediation Event Observations) code of the event, which describes in detail the type of the occurred event, (e.g. "Reject accusation, deny responsibility", "Appeal for easing of administrative sanction" or "Express intent to meet or negotiate"). There are hundreds of these codes, which are already grouped by overall theme that can help us increase the accuracy of our analysis.

Another interesting value contained in each event is the "Goldstein score" which tries to capture the theoretical potential impact that type of event will have on the stability of a country. This can possibly be used to "weigh" the impact of an event on the future progression of the socio-political issue at hand.

A supplement database that can be used is the UCDP External Support Dataset. This dataset provides information on the existence, type, and provider of external support for all warring parties, on an annual basis, between 1975 and 2009. This database can be used to enrich the existing data and identify possible foreign interventions in the examined process. Other UCDP datasets that could enrich our analysis are UCDP Conflict Termination Dataset and UCDP Peace Agreement Dataset, which could provide us with some important data points relevant to the further exploration of this subject.

Another possible dataset that we would like to explore in the context of this project is the Twitter dataset, however as it is not currently available we cannot definitively determine it's ultimate function. Once it becomes accessible, we intend to take some time to investigate the potential sentiments and events in the post-Twitter era that could refine our dataset for the observed period.

# A list of internal milestones up until project milestone 2

In the next period we intend to focus on detailed analysis of the provided datasets that will be used in our project.

The main intention would be to find all of the features that could have a significant correlation with the phenomena we are exploring, and all of the limitations we could overcome by enriching our final dataset with other complementary datasets.

The first phase would include the further investigation of the data in the GDELT dataset and this step should be completed during the **first week of November**. The overall plan would include the recognition of the most important columns and event types that could be useful for the analysis. We would also devote a significant amount of time to clean all of the possible inconsistencies and transform the data so that it is more suitable for further wrangling and merging with other datasets, since this database will be the basis for our reasoning.

The second phase would be more inclined toward the research of the data in the UCDP dataset and this step should be completed during the **second week of November**. Most of the analysis of the UCDP dataset would be focused on the identification of events and conflicts that demonstrate the existence of the phenomenon in a country, and merging the extracted data with the dataset from previous phase.

The third phase would be directed toward the inspection of the potentially useful data in the Twitter and complementary datasets, so this step is going to be unfolding after the previous phases are finished, in the **last weeks of November**. The main motive would be to finalize the dataset for this project by including some unbiased evidence that could improve the inferences in the following steps of the analysis.

In conclusion, this period is going to be the one that helps us gain a greater understanding of all the datasets we plan on using. Our main goal is to develop a unified dataset that is cleaned, pre-processed and ready for upcoming analysis.

# A list of internal milestones up until project milestone 3

During the next three weeks we plan on finalizing our analysis.

Our work during the **first week of December** would entail accessing the complete dataset via the cluster (if it becomes available there) or by some other means. Parallel to that, we plan on exploring the data even more and finding the best way to combine and filter the GDELT events and combine them with the UCDP datasets.

By the end of the **second week of December**, we plan on completing the full analysis of each of the observed countries in our datasets.

Finally, in the **third week of December** we will see whether we can apply the insights from our analysis to the regions that are currently showing signs of possible independence, possibly applying some Machine Learning techniques to observe and predict future trends.

# Questions for TAs
