# Project_ETL

### DataSets
***

- World Cities Population & Location
    - csv file
    - https://www.kaggle.com/i2i2i2/cities-of-the-world
  
- Countries ISO Codes
    - csv file
    - https://www.kaggle.com/juanumusic/countries-iso-codes
  
- Cost of Living Index by Cities
    - csv file
    - https://www.kaggle.com/debdutta/cost-of-living-index-by-country
    
###  A preliminary sketch of your database (type of DB, tables, etc)
***
Preview of Transformed Databases
- World Cities Population & Location
![image](https://user-images.githubusercontent.com/42760390/55673486-42179780-586e-11e9-9a25-072df2067819.png)


- World Cities Population & Location:
![image](https://user-images.githubusercontent.com/42760390/55673516-8440d900-586e-11e9-9032-dd4f09ad3c7d.png)


- Cost of Living Index by Cities:
![image](https://user-images.githubusercontent.com/42760390/55673537-ccf89200-586e-11e9-98bf-2be29808a791.png)


### Preliminary list of necessary data transformations
***
Countires ISO Codes:
create a dataframe that only contains English shortname(lowercase) and  alpha-2 code columns

World Cities Population & Location:
create a dataframe that only contains the county code, name, population columns
create primary key index from conunty name

Cost of Living Index by Cities:
create a dataframe that only contains the cost of living data and cities, country columns.  The citiy and country column will need to be dirived from the single city column in the dataframe (comma delimited).




