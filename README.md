# Call-Centre
This analysis is to find trends and insights using some visuals and understand the performance of this particular Call Centre.
## Data Preparation
I had a glance of the dataset using excel and I was able to find out that the data consists of 10 columns and 5001 rows with the column names as Call Id, Agent, Date, Time, Topic, Answered (Y/N), Resolved, Speed of answer in seconds, AvgTalkDuration and Satisfaction rating.
![image](https://github.com/shirfil333/Call-Centre/assets/107877851/bb4f6dc4-5467-4071-a98c-3f3249e6e852)

After taking a glance at the dataset, I moved to Power BI and connected to the dataset then did some cleaning and processing in the power query editor such as:
### 1. Replacing the null values in some columns with 0. Replacing null with 0 isn’t the only way to treat null values but I chose to replace with 0 because there were no trends in those columns to say I want to follow existing trends neither do I have access to the stakeholders to give me an insights as to why those cells had null values hence, resolving to 0. I couldn’t replace the AvgTalkDuration with 0 because it can’t take any value that isn’t in the time format.
### 2. Changed the N and Y in Answered (Y/N) and Resolved to Yes and No which people could easily relate with.
### 3. The “AvgTalkDuration” column name was changed to “Avg. Talk Duration” and initially, the column consisted of both time and date but i changed the data type to only time since it was talking about duration and it was on a particular day.
### 4. Just like the Avg. Talk Duration column, the time column also consisted of both time and date so i basically changed the data type to reflect the time only.

After doing those cleaning and processing, the data looked cleaner to work with DAX.

## Conclusion
All the visuals created sum up to a dashboard to further draw more insights and a full picture of the dashboard created is shown below.
![image](https://github.com/shirfil333/Call-Centre/assets/107877851/78f85807-03c0-4c6f-b540-f59e9487b76d)
