# EC601_Project
### Project 2: Minimum Value Product Report from Sentiment Analysis using NLP APIs
#### Project Goals
The goal of this project is to provide a Minimum Value Product for a product using sentiment analysis using both Twitter and Google NLP APIs. 
The overall process is to use a Twitter API to grab and make text database that sentiment analysis NLP API can then analyze for the sentiment of each tweet. 
For this project, the focus became to use NLP API rather than any Twitter APIs after running into access errors while trying to use Botometer and other Twitter-based APIs. 
The database for sentiment analysis was grabbed from one of previous Kaggle competition called "Tweet Sentiment Analysis" and analyzed using a sentiment analysis API. 

#### Report
A minimum value product in tweet sentiment analysis might be a Twitter user or corporation who is interested in learning more about user replies or what types of emotion their tweet comes across as. They might also be interested in tweets that have done particularly well, such as tweets with highest likes or tweets that have been retweeted more than others. For this report, MVP for this product will be learning what types of emotion a tweet evokes and their spread in different categories for a user. This MVP could be useful for influencers or corporations who have high interest in understanding the general sentiment of their tweets. 

`Screenshot of Botometer Error`
![Screenshot 2022-12-15 at 6 17 07 AM](https://user-images.githubusercontent.com/91296660/207845894-d8d5afbd-d25c-4a7f-bae3-cf87dd879bec.png)

I was unfortunately not able to work on the error for Botometer - even though I separately requested access, it was not able to go through. 

Instead of using Botometer, I was able to access some tweet database through Kaggle, and decided to work with the data provided by them. 

`Train data from Kaggle`
![Screenshot 2022-12-15 at 6 29 24 AM](https://user-images.githubusercontent.com/91296660/207848253-ec255775-822e-460c-bc2b-7b34d9eb084c.png)

The train data from Kaggle was organized by the text ID, text, selected text, and the sentiment - divided in neural, negative, positive categories. 

`Grouped by sentiment and given general description of data`
![Screenshot 2022-12-15 at 6 31 24 AM](https://user-images.githubusercontent.com/91296660/207848677-921cd5fd-6096-4590-bf29-fae5a18bdee1.png)

Unfortunately, I was not able to get Google NLP sentiment analyzer to work. 


#### Conclusion

#### References
#### DATA SOURCE
https://www.kaggle.com/competitions/tweet-sentiment-extraction/data
