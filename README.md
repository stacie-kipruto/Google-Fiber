# Google-Fiber
![image](https://github.com/stacie-kipruto/Google-Fiber/assets/66944986/905b51c4-0687-4156-be48-951885d97864)




## Background
- The team needs to understand how often customers  phone customer support again after their first inquiry; this will help leaders understand whether the team is able to answer customer questions the first time. Further, leaders want to explore trends in repeat calls to identify why customers are having to call more than once, as well as how to improve the overall customer experience. A dashboard should be created to reveal insights about repeat callers.

## Data Sourcing and Consolidation
- The data was provided by the Google Fiber Team in form of CSV files
- The data was ingested into BigQuery and a UNION ALL statement is used.

![image](https://github.com/stacie-kipruto/Google-Fiber/assets/66944986/53854046-ef5d-4ac7-9270-9f4454868f9e)


- This query combines all the data from three different tables (`market_1`, `market_2`, and `market_3`) into a single list. It uses the `UNION ALL` command, which ensures that every row from each table is included, even if there are duplicates. It merges the tables' contents without any filtering.
- The result was then saved into a CSV to be used in Tableau for analysis.
