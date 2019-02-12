# Google_Playstore_Apps
This is a simple Exploratory Data Analysis of Google Play Store Apps Dataset from Kaggle. I have used seaborn for the visualization.

This is a Kaggle dataset on Google Play Store Apps. I chose this data set to visualize some of the trends in apps downloaded by the users.
First and foremost, the dataset was loaded into pandas dataframe. This dataset consists of 10841 rows and 13 columns.
Data Cleaning
- The total number of Unique Apps in this dataset are 9659 and all the duplicates were dropped.
- Since the size of the apps were not consistent throughout, I converted size of all the apps to 'Mb',
- The 'Installs' column had '+' sign and so to make this a floating point data type, I removed the '+' and converted the data type to float.
- The 'Price' column had '$" symbol which I have removed and again converetd the datatype to float. 
Visualization
- The basic pie chart shows the distribution of the apps in each category based on the total number of apps in each category.
- The average rating for all the apps is 4.17 which is pretty descent. Most of the apps have pretty descent ratings except a few in categories like business, medicl, dating, finance,game, family, tools and productivity
- Apps which had more than 1000 installs were analysed to see the trend in price
- From the data, we can see that users tend to install apps which are free and priced between $1 - $30.
- There are couple of apps which are priced more than $100 and there are about 1M users and the rating for the expensive apps range between 3.0 - 4.2

