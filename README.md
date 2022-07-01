# Dig Hum 101 Project
## Sentiment Analysis of Reddit Political Communities
#### Research Question: Do different political subreddits have measurable differences in sentiment (positive/negative) when communicating about the same current evennts?
#### All applicable code and data for this project is found in the jupyter notebook attached.
###### Note: Results may vary from the following images as code pulls most recent data from Reddit.
#### Results from June 30, 10AM PST:

![Headline Sentiment](https://github.com/rayleehe/dh101sum22/blob/main/headline%20sentiment%20bxplt.png)
![Comment Sentiment](https://github.com/rayleehe/dh101sum22/blob/main/headline%20sentiment%20bxplt.png)

Abstract: This project used VADER lexicon sentiment analysis to look at different political subreddit headlines and top-level comments. The goal of this project was to determine whether different political subreddits react in measurably different ways to the same current events. To achieve this, Reddit API was used to pull a list of headlines and comments from the subreddits: r/Politics, r/PoliticalCompassMemes, r/SandersForPresident, and r/Conservative. r/Politics and r/PoliticalCompassMemes were chosen as these communities are meant to represent all kinds of ideologies and thus should be neutral. r/SandersForPresident and r/Conservative were chosen as these communities are the largest left leaning and right leaning subreddits.

Results: Overall, r/Politics ended up being the most negative community by sentiment score. r/SandersForPresident and r/Conservative predictably had sentiment scores opposite of each other. If reacting to the same current events (i.e. Supreme court overturning Roe v. Wade), we expect one side to react positively to news while the other to react negatively. One interesting finding however is that while r/SandersForPresident had more positive headlines and r/Conservative more negative ones, r/SandersForPresident had more negative comments compared to those left in r/Conservative.
