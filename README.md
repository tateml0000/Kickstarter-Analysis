# An Analysis of Kickstarter Campaigns
Performing Analysis on Kickstarter data to uncover trends

## Overview of Project
  For this project I am helping a playwriter, Louise, an up and coming playwrite who is looking to start a fundraising campaign for her project. She has a budget of $10,000, and is looking to find the best way and time to raise this money. In order to do this we must analyze previous fundraising campaigns all around the world in different areas of the arts, and try to determine the best method to go about raising money. This will include evaluating the time frames, location, and asking amount of each project, and determining whether or not it's viable for Louise to start a project at a given goal.

## Analysis and Challenges
Here we will be looking at a few analysis and challenges that came along with this. Since this project was done in a short amount of time, we can look at what things went well and what we were able to determine, as well as things that may have been missed, or should be looked further into.

### Analysis of Outcomes Based on Launch Date
In this 2 part analysis we began by looking at the successful, failed, and caceled outcomes of theater campaigns. In the chart below, titled "Theater Outcomes Based on Launch Date", we can first note that very few campaigns were canceled regardless of the month. This could be due to a variety of factors, including faith in the fundraising, initial success, a reorganized plan, or a multitude of human factors that we may not be aware of. The next obvious trend to see is the success of campaigns in May. Although May also had the most amount of failed campaigns, only by 2 to July, we can see that the late summer into the early spring would be an optimal time to begin a campaign. 

![Graph of Outcomes Based on Launch Date](https://github.com/tateml0000/Kickstarter-Analysis/blob/main/Theater_Outcomes_vs_Launch.png)

Some challenges while analyzing this data were fairly straight forward. We do not know the exact amount of each of the campaigns in may so an analysis further into this would be helpful. Comparing the success of each of these campaigns in goals as well as country would help us determine whether Louise's $10,000, US campaign would be viable, or maybe we should look into a different month where we may find less overall succeses, but the majority of those come in the US with a goal of around $10,000.

### Analysis of Outcomes Based on Goals
The second part of this analysis was to look at the specific fundraising goal amounts of campaigns, in the subcategory of plays. We sorted each play campaign into its own bucket of goal amount and found out the total number of successes, failures, and cancelations. Here, much like the first analysis, we can see a very low number of cancelations, actually 0 of them. This comes with a lot of questions, but this would have to be looked further into with interaction with the campaign starters, and cannot be looked at from a data side, since we do not know the reasoning behind these cacelations The second thing we can observe in the chart below, is a general downward trend in successfull campaigns as the goal buckets increased, simulataneously the failed campaigns were increasing. This means that we can assume, the higher the fundraising goal, the less likely it is to succeed, while a a lower fundraising goal is more likely to succeed. The point at which these are equal is in the $15,000-$19,000 bucket. 

![Graph of Outcomes Based on Goals](https://github.com/tateml0000/Kickstarter-Analysis/blob/main/Outcomes_vs_Goals.png)

This would bode well for Louise as her goal would be lower than this, indicating a higher chance at success. Unfortunately we do not have all the information we need in this chart to simply make a decision based no these buckets. We should be wary of other factors such as location of these campaigns as well other outlying factors that may not be included in the data set, such as was the playwrite successful previously, and how many backers did each of these plays have. These would be crucial in determing campaign prospecting and could drastically affect the results if not enough backers were reached or the average donation of the backers was not in line with these numbers we see here.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

	1. May and June are the two most successful months to launch a theater campaign.
	2. December is the worst month to have a theater campaign since the failed outcomes is roughly the same as the successful ones.

- What can you conclude about the Outcomes based on Goals?
	1. A general trend can be found by observing the data, that the lower the goal, the better chance at success. Although having a low goal doesn’t guarantee a successful campaign. We can also see that there are more campaigns with lower amounts, which means we don't necessarily have enough data to determine the exact outcomes based on goals with the amounts, we just can say they are less likely to occur. This is also a reason we are seeing varying numbers in the graphs when it comes to a percentage because the difference a single campaign in that bucket could vary the results by 25% in either direction or more.

- What are some limitations of this dataset?
	1. We know that this data set is not representative of all possible campaigns, just ones that are focused in this specific area, which could be trending in a different direction based on the timeframe.
  2. There are plenty of other factors that could inhibit donations that we cannot quantitatively observe such as likeability of the person or project, or a close network of friends and family that are willing to back the project and get a head start.
  3. We tend to use the world for these campaigns and don't always limit it to the country that this campaign will happen in. This causes issues in data because one industry could be booming in another country while falling in a different one.

- What are some other possible tables and/or graphs that we could create?
  1. We could compare theater campaigns in the US based on year to find out whether they are getting higher donations as it gets closer to the current year or maybe things are trending downwards. 
  2. A chart that focuses specifically on the highs and lows. So for the launch date, we could take these campaigns in May-July and just chart them looking at goal, pledged, backers, and successful vs. failed to see the similarities and differences in these "successfull" months. The same could go for months like December to try and guage what is going right and wrong.
  3. We should also look at a table and chart of date created and date ended to find out the length of these campaigns to determine whether a shorter time frame or longer time frame would be more beneficial. Short time frame could create urgency causing more backers sooner, while a longer time frame could encourage procrastination from backers to see how the campaign is doing before committing. This could cuase lower numbers and a worse outcome if so.

