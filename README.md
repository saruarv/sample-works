INSIGHTS for data challenge from Maven Analytics

120 Years of Olympic History
   About the dataset
This dataset contains 2 tables, in CSV format:

1.The Athlete Events table contains over 270,000 Olympic performances across history 2.Each record represents an individual athlete competing in an individual event 3.Records contain details about the athlete (ID, sex, name, age, height, weight, country) and the event (games, year, city, sport, event, medal) 4.The Country Definitions table serves as a lookup table with “NOC” as the primary key 5.Each record represents one country according to the National Olympic Committee.

visualization tool - Microsoft PowerBi
 The data's are given in a csv text format.The following steps are done to submit a single page visualization with insights
1. Importing the data into powerBi
2. Transforming the data ---making first row as headers,checking the datatypes for all columns,date conversion.
3. checking the levels of data.
4. checking for NUll values and replacing them .
5. DAX is used to calculate the percentage of female athletes over time,top countries winning medals,top athletes,top sports.A slicer is added to distinguish between the summer and winter games.
