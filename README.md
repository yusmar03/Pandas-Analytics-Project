

# Project XYZ

This project process is trying to explore the data gathered by the company XYZ. It intends to do so by parsing the data into meaningful representations using pandas, plotting graphs to pick out informative insights using seaborn and recommending the appropriate further actions to be taken by the company depending on what the insights are

# Project Steps

Step 1: The necessary python libraries were imported, the csv files for each city was loaded and concatenated into a mother csv file

Libraries Imported

Pandas
glob
os

Methods Used

.concat()
.map()
.chdir()
.glob()
.read_csv()
.to_csv()

Step 2: This step involved checking details about the data

Libraries Imported
.pandas
. seaborn
. warnings
.numpy
.matplotlib.pyplot

Attributes Used

.Columns
.shape

Step 3: This step involved the parsing of the Date and Time column into new Day, Month, Year and Hour columns

Libraries Imported

.datetime

Methods Used

.to_datetime()
.info()
.nunique()
.unique()

Attributes Used

.hour
.month
.year
.day

Step 4: Categorical type columns were looked into in this step.

Methods Used

.unique()
.tolist()
.value_counts()

Step 5: This step aggregates the data by some columns so statistical information like mean and sum can be gotten for those aggreated columns

Methods Used

.groupby()
.max()
.sum()
.idmax()
.agg()

Step 6: Plots were created using the data in this step. These plots show some very important information that gave insights which will be discussed in a later section of this report.

Plots Created

.countplot
.boxplot
.catplot of 'swarm' kind
.catplot of 'point' kind
.catplot of 'strip' kind

Methods Used

.set_title()

# Insights

1. 'Food and beverages' products tend to bought more in bulk
2. Epay is the most used payment
3. 'Health and beauty' products are mostly bought by females
4.Lagos marks the most sales
5. Fashion accessories' is the most bought product line
6. Branch 'A' marks the maximum branch sales
7. The maximum gross income coming from Port Harcourt is XYZ most frofitable city
8. 'Electronic accessories', is the product where epay is used most

# Future Work


XYZ should ensure that the store shows up in online search results
Now more than ever, consumers are turning to Google to find stores and products. Make sure that is showing up whenever they conduct a search relevant to the business. If you sell baby clothes, for example, then you want nearby customers to find your business whenever they run a search for “baby clothing store near me.”

You can do this by setting up business listings on Google, Yelp, Facebook, and other platforms.

# Standout Section

.I parsed the 'Date' column using strftime() method to create a new column 'Day_words' that stores the day in English. (Example: 1 would be 'Monday' and 7 would be 'Sunday')
.I then created a catplot (kind = 'count') of the newly created 'Day_words' column to show how:
Saturday, followed by Tuesday are the most popular days for shopping in Company XYZ's stores
Monday is less busy day at Company XYZ's stores
.I created a countplot of the 'Customer type' column with the hue parameter set to 'Gender' to show how:
XYZ has more female customers than male

# Executive Summary.
Can be found in 

