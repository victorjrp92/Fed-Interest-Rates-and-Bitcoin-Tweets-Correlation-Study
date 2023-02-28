# **Hypothesis**

The hypothesis of this study is that there exists a correlation between the Federal Reserve's interest rate policy and the frequency of tweets related to Bitcoin on Twitter. Specifically, the hypothesis proposes that when the Federal Reserve increases interest rates, there will be an increase in the number of tweets related to Bitcoin on Twitter a couple of days before the interest rate hike, followed by a decrease in the number of tweets in the days and weeks following the interest rate hike. This study aims to provide empirical evidence supporting this hypothesis by analyzing Twitter data and interest rate policy announcements by the Federal Reserve.

![fed](imagens/fed.png)

### **Methodology**

This study involved the analysis of data related to Bitcoin tweets and the Federal Reserve's interest rate policy over the past three years. The data on Bitcoin tweets was obtained from Kaggle, but due to its large size (2.5 GB), it was cleaned and a lighter version was used for analysis. The cleaned data was used to create two new columns, one for calculating the sentiment of the tweets and the other to categorize the tweets based on their sentiment level.

The resulting DataFrame was exported to SQL, and two queries were created from it. The first query categorized the sentiment of the Bitcoin tweets over the past three years, analyzing how the sentiment changed over time and identifying key events that may have affected sentiment levels. The second query analyzed the sentiment of Twitter influencers over time.

To obtain data on the Federal Reserve's interest rate policy, Beautiful Soup was used to scrape data from the Federal Reserve's website, resulting in a DataFrame of interest rates for the past three years. This data was also cleaned and sent to SQL for analysis.

All queries were then sent to Tableau for visualization, where graphics were created to help analyze and understand the relationships between interest rate policy and Bitcoin sentiment on Twitter over the past three years.

[project4](https://public.tableau.com/app/profile/victor.ramos6833/viz/project4_16775785624060/Story1?publish=yes)

### **Observation**

The first dashboard reveals that the average sentiment of Bitcoin tweets in 2021 had fewer negative tweets and more positive ones. During that year, the Federal Reserve did not increase the interest rates. However, in 2022, the sentiment changed, and people on Twitter became more pessimistic about the market situation. As a result, the positivity of Bitcoin tweets decreased. This suggests that changes in interest rates by the Federal Reserve may have an impact on the sentiment of Bitcoin tweets on Twitter, and that sentiment can shift quickly depending on market conditions. These observations can provide valuable insights for investors and analysts looking to understand how changes in interest rates may affect the cryptocurrency market.


### **Conclusion**

The analysis of Bitcoin tweets and the Federal Reserve's interest rate policy over the past three years provides valuable insights into the relationship between these two variables. The sentiment of Bitcoin tweets on Twitter appears to be affected by the Federal Reserve's decisions on interest rates. The sentiment shifted quickly in response to market conditions and changes in interest rates, with a decrease in positivity observed in 2022 following the Federal Reserve's decision to increase interest rates.

However, it is worth noting that the amount of Bitcoin tweets on Twitter did not decrease, despite changes in sentiment. This suggests that people on Twitter are still interested in discussing Bitcoin even in times of market uncertainty, and that Twitter can serve as an important platform for monitoring sentiment and identifying trends in the cryptocurrency market.

Overall, these findings can be useful for investors and analysts looking to better understand the factors that drive sentiment in the cryptocurrency market and how changes in interest rates by the Federal Reserve may impact the market in the future. Further research can build upon these insights by examining other variables that may influence sentiment and exploring how sentiment affects the behavior of investors in the cryptocurrency market.