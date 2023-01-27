# The-Investors-Dilemma
Analysing start ups and funding in India.
The project will analyse data from Indian startups from 2018 to 2021 to draw insights on the Indian startup market and funding. 


## Business Understanding

HYPOTHESIS

Null hypothesis - Investors interest in startups are directly correlated with the startup industry
Alternative hypotheses - Investors interest in startups are independent of startup industry

QUESTIONS

1. Which startup industry/sector attracts more investors?
2. Does investment amount correlate with the age of the startups?
3. Does the location of the startup affects investors interest in investing?
4. Which funding year saw investors investing more into startups?
5. Which stage of funding receives the most funding?

6. Is there a relationship between investor amount, location of startup and industry of startup?


## Problems With the Data

MAJOR ISSUES

1. Wrong datatypes
2. Missing values
3. Combination of non-printable characters with strings (2018 data)
4. Amount column having two different amount in the same row
5. Misplaced values (the stage column having amount information and amount column having stage information, 2019-2021)
6. Inconsistent column names


PROPOSED SOLUTIONS

1. Change to appropriate datatype
2. Replace empty rows with missing values and dropna values or fill with a mean or median
3. Remove all non printable characters
4. Delete those rows or fill with one value
5. Rearrange values correctly
6. Change column nam

## Insights

At the end of the exploration, it was discovered that the type of industry the startup is in affects the investment. We realized that more startups in Fintech and Edutech received significant amounts of funding as compared to startups in logistics and food and beverages. 
We also came up with the conclusion that the location of the startup greatly affected the funding it received. This is evident in the fact that startups in the higly dense cities such as Bangalore and Mumbai received the highest number of fundings. There was also a strong correlation between the age of the startup and the funding received where startups founded earlier received more funding thand the most recent ones. 