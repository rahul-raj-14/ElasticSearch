#### Context
We all want to know about the good food and quality of food in our area.
#### Content
Content is placed in the data/zomato folder
1. We Used zomato.json for our research which is combination of Country-Code.xlsx and zomato.csv
2. Data is taken from the https://www.kaggle.com/shrutimehta/zomato-restaurants-data highly appreciated for that
3. Data can also be collected from the Zomato API(https://developers.zomato.com/documentation)
4. We put the json data in the elastic search through bulk api

#### Research
1. Different type of aggregation provided by the elastic search.
2. In agg_01.txt we are getting the result according to the Country (records according to Country)
3. In agg_02.txt we try to achieve the aggregation according to Country(India) and Locality ,Country(India) and (Cuisines and Rating Colors)
