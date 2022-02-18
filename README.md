# ReadMe

## Sabrina Starr DSI GA Project 2

## Problem Statement
What effect does overall quality and above ground living space have on the sale price of a home?


### Data Dictionary
Link to data dictionary: http://jse.amstat.org/v19n3/decock/DataDocumentation.txt


### Datasets
Train CSV and Test CSV from Kaggle https://www.kaggle.com/c/dsir-0124-project-2-regression-challenge/data


### Additional research

-'Understanding your aviatar record card' allowed me to deepen comprehension on column categories, such as the importance of distinguishable lot seperation and lot layout in the interpretable value of a home. https://avitarassociates.com/Portals/0/PDF/UnderstandingYourPropertyRecordCard.pdf 

-Train and Test CSV data dictionary http://jse.amstat.org/v19n3/decock/DataDocumentation.txt



### Summary of Analysis
I was able to use train-test split, cross-validation, and data with unknown values for the target to simulate the modeling process using a linear regression model with the features overall home quality and above ground living area to make the following analysis:
All else constant, for each unit (square foot) increase in above ground living area, our model predicted a $56 increase. All else constant, for each unit increase in the overall quality of a home, there was ~$33,000 increase. The original data sale price distribution was skewed right, meaning it was less common to see more expensive homes. In terms of the model performance, the model tends to do worse with more expensive homes because there were less of them strewn within our data.

### Conclusions and Recommendations
**Conclusions:** Capitalizing on overall home quality while selling a home will increase it's sale value. Suggesting a new tile job for the kitchen backsplash, new hardwood floors, etc. helps with maximizing profit and quickening sale time of the home.

**Recommendations:** Focus on home material and finish quality, to still pay attention to square footage above ground (or grade) living area, but to prioritize quality first.

**Project Recommendations:**
Other recommendations with more time include adding more interaction terms, such as an interaction term between living area and quality. I would do more analysis on the highest correaltive features to sale price as well. I would also complete more algorithm tuning; as well conduct a deeper analysis into my ridge regression model. I would also scale my data to fit into a lasso regression model as well in hopes of increasing model accuracy. 




