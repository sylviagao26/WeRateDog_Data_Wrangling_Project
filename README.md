# Introduction:

This is a data wrangling project build for twitter data WeRateDogs. 

WeRateDogs is a Twitter account that rates people's dog with comments and the ratings of the dog in a humor way. Before further analysis and create intersting viuslization of the data, we need to download tweets, clean data and make it to be more structured, accuracy and analysis friendly strucutre.

We have tweeter archive data, which is provided and rough segment, we will also use twitter API to query each tweet's JSON data. Additionaly, we also get the data that use neural network classify breeds of dogs through dog image based on each tweet's picture.

After gathering all the data, we need to briefly access the data, identify any quality issue or untidy issue. Then clean the data, fix any tidiness or quality issue, deliver cleaned data and prepare for further analysis.

Then we will try to analyze and visualize the wrangled data, delivery interesting insights and data visualization.

# The dataset used in this project:
 
1.`twitter_archive`The WeRateDogs Twitter archive. This is provided by udacity course and download as csv file 'twitter_archive_enhanced.csv' 

2.`tweet_image_prediction` The tweet image predictions. Accroding from the neural network model, the breed of dog is present in predicted by each tweet's dog image. This data is hosted on Udacity's servers and will be programmatically download using Requests library from the following url: https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv

3.`tweet_collect` Gather each tweet's retweet count and favorite count to get futher info. Using the tweet IDs in the WeRateDogs Twitter archive, query the Twitter API for each tweet's JSON data using Python's Tweepy library and store each tweet's entire set of JSON data in a file called 'tweet_json.txt' file.

# The library used in this project:
pandas

numpy

requests

os

tweepy

json

matplotlib.pyplot

seaborn
