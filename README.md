# VideoGameSales
Stats Final Project - Team Nugget


# Source and inspiration
Kaggle: https://www.kaggle.com/ashaheedq/video-games-sales-2019

We like video games. We are interested to see the correlation between video game critic scores and sales as well as other questions relating to the video game industry. For this type of question, we would look at correlation and how the relationship has changed over time as well as for different countries. We can also ask other questions such as which publishers have the highest sales? Best reviews? How has video game sales changed over time? Geographically? What does the relationship between genre and sales look like? Genre and reviews? Which genres are more popular in each market?
The data was scraped from http://www.vgchartz.com/gamedb/ using Python April 12th, 2019 and was hosted on Kaggle.



# Data Dimensions
Observations: 55,792
Variables: 23


# Description of all variables

|Variable Name |Description                                            |
|--------------|-------------------------------------------------------|
|Rank          |Rank of overall sales compared to other games          |
|Name          |The title of the video game                            |
|Basename      |The name of the video games, but with “-” instead of “ ”|
|Genre         |Genre of the video game                                |
|ESRB_Rating   |Rating of the video game from K to A0                  |
|Platform      |The console the video game was released on             |
|Publisher     |Name of who released the video game                    |
|Developer     |Name of who made the video game                        |
|VGChartz_Score |A numeric score from 0 to 10, is the score of a VGChartz reviewer|
|Critic_Score  |A numeric score from 0 to 10, is an average of the critic scores across popular video game sites. |
|User_Score    |A numeric score from 0 to 10, is an average of the user scores on the website VGChartz.com|
|Total_Shipped |Total copies games shipped measured in millions        |
|Global_Sales  |Sales of the video game across all markets measured in millions of US dollars|
|NA_Sales      |Sales of the video game in North America measured in millions of US dollars|
|PAL_Sales     |Sales of the video game in Europe measured in millions of US dollars|
|JP_Sales      |Sales of the video game in Japan measured in millions of US dollars|
|Other_Sales   |Sales in the rest of the world measured in millions of US dollars|
|Year          |The year the game was released                         |
|Last_Update   |The date of the last edit to the video game’s webpage entry|
|Url           |The url link to the video on the website               |
|Status        |1 for all rows, will not be used.                      |
|Vgchartzscore |A numeric score from 0 to 10, is the score of a VGChartz reviewer|
|img_url       |The website URL of each entry                          |
