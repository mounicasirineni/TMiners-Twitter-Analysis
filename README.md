# TMinersTwitterAnalysis

The goal of this project is to develop a single web application for a user to enter a keyword and perform two tasks:

I.	Visualize the density distribution of tweets about the keyword across United States map.

II.	Sentiment classification of tweets associated with the keyword and their distribution.

"Code" folder contains the Java code of this project.

Document "Project Report" describes the project.

Application front end is developed using JSF framework and the back end analysis is performed by Hadoop MapReduce jobs.

MongoDB is used to store state and city details of United States.

Tweets are retrieved for the specific keyword using Twitter4j API.

User profile location from tweets is used to display the density distribution on heat map using AmCharts.

Analyzed sentiment associated with the keyword using LingPipe API.

Classified tweets as Positive, Negative and Neutral and generated pie chart using JFreeChart.

