# Overview of the statistical analysis:
This analysis is about weather condition on an island named Oahu in Hawaii. The person is trying to open Surf n' Shake Shop in Hawaii and is keen to find an investor who can fund his business. He came across an investor, W Avy, who is interested however his past experience was not good investing in the same business as his past venture was rained out of business due to weather and this time W Avy wants to get into this business only after running a detailed analysis on the weather in Oahau island for the past 7 years. The person, who wants to open the business, will be running analytics on weather datase that W Avy has from the very island where he wants to open the shop.

# Results:
Three major points from the two analysis deliverables is as below:

    1)  The maximum temperature in the month of June was 85.00, and the maximum temperature in December was 83.00. This clearly shows that the maximum temperature in the month of June & December does not have much difference and if the person plans to do business in June in Oahu, then he/she should not face any issues operating in the month of December as well.
    
    2) The minimum temperature in the month of June was 64.00, and the maximum temperature in December was 56.00. This clearly shows that the minimum temperature in the month of June & December does have difference but it will not have positive impact on the business as the person is planning to sell ice-cream and surf shop and if the temperature falls in December then it will not be profitable for selling ice-cream & surfing
    
    3) The mean (average) temperature in June was 74.94 and in December was 71.041 hence it is proved that there is not much difference in average temperature for the month of June and December in past 7 years
![image](https://user-images.githubusercontent.com/96365651/156894562-a165af38-4312-4348-89af-bc91af81a885.png)
![image](https://user-images.githubusercontent.com/96365651/156894567-db9cfb87-7f7c-4e67-8f61-390edf594a32.png)


# Summary:
The result shows that it is profitable to start Surf n' Shake Shop in Oahu island considering few things. There may be a situation where business could be impacted in the month of December due to weather conditions, however for the majority of the months the business could be profitable and there will be visitors who will be intersted in buying shakes, ice-cream and surfing. Also, below mentioned are further 2 queries so that investor could get more detailed understanding about the weather by looking at charts. I have included it in my final submission in SurfUp_Challenge.ipynb file
________________________________________________________________
** Sort the dataframe by date

df.set_index(df['date'], inplace=True)

df = df.sort_index()

** Use Pandas Plotting with Matplotlib to plot the data

df.plot()
_________________________________________________________________

** Plot histogram

df.plot.hist()

___________________________________________________________________






