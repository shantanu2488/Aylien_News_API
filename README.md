# Aylien_News_API

News Intelligence can be the difference for large organisations to identify risks and opportunities early, allowing them to take quick and decisive action when needed. Often, all that is needed is one news story, one needle in the haystack to trigger an alarm or to identify a gap in the market. 

AYLIEN’s Timeseries endpoint empowers us to do this. With this endpoint, we can track changes in quantitative values contained in stories over time. This information can be anything from mentions of a topic or entities, sentiment about a topic, or the volume of stories published by a source, to name but a few. It is also much faster to pull aggregate Timeseries data then it is to query the stories endpoint and return individual stories in batches and subsequently process them to measure the occurrences of entities, sentiment etc. contained in each article.

**Visualizing Timeseries**

Visualizing Timeseries data is a quick and efficient way for identifying spikes, anomalies or other points of interest and is a great springboard for identifying areas of further investigation using granular stories. 

![how_to_use_timeseries_line_graph_labels](https://user-images.githubusercontent.com/26651731/111426199-4e732300-871a-11eb-9fb4-b3dfd3172511.png)


Using the Stories endpoint, we can then extract the highest Alexa ranked story for the corresponding time period. Appending the title of this article to our graph gives us a good indication of the focus of the content. Alexa Ranking is an estimate of a site's popularity on the internet.

**Pulling Timeseries by Sentiment**

In Media Monitoring, sentiment analysis is an invaluable tool for tracking brand sentiment, the success of campaigns, public relations and monitoring crises. It can act as the acid test for public opinion and serve as a vital indicator of how a subject is perceived. 

![how_to_use_timeseries_line_graph_sentiment](https://user-images.githubusercontent.com/26651731/111426245-5fbc2f80-871a-11eb-8b47-98a8330906a5.png)

With the Timeseries endpoint, we can aggregate the stories that meet our search criteria and analyse their sentiment en masse. While AYLIEN’s News API classifies documents and entities as having a positive, negative or neutral sentiment, focusing on the polarised positive and negative stories only gives us a better indication if a subject is being viewed in a good or bad light.


Kudos!!



