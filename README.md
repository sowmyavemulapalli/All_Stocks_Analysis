# VBA STOCKS ANALYSIS

## Overview Of This Project
    - This Project is dealing with Stocks data of Particular individual in 2018 and 2017. The data set contains the data of all the stocks he has in  2018 and 2017.

### Purpose 
      - The Purpose of this project to calculate the whether he has positive or negative returns in all the shares he has in 2017 and 2018 and also to caluculate the total volumes also.

## Results
    
    -  I have obtain the two results one is Total volumes and return percentage in 2017 with in 0.109375 seconds and the other one return percentage in the year 2018 within 0.1035156 with the screenshots included below.
    -I have calculated these percentages for each ticker by finding the tickerstarting prices and tickerending prices with the condition if the current row is the first row for that ticker then assign cell(i,6) to starting prices and if the current row is ending row in that ticker then assign cell(i,6) to the ending price. In the year 2017 the profit percentages are more for all other tickers except TERP. But in 2018 year tickers  ENPH and RUN have positive percentage while remaining tickers have negative percentages. 

![image](https://user-images.githubusercontent.com/86328230/124404391-56be9080-dd00-11eb-9ba5-efd068a38786.png)
![image](https://user-images.githubusercontent.com/86328230/124404489-c46abc80-dd00-11eb-9e52-2c33f63ceae3.png)







## Summary
  - The Summary of this project is by refactoring the code there are lot of advantages, some of them are we can increase the readability, easy development,maintenance, automation and performance improvement.


  
### Pros
  - The pros of this vba script is this automation will make the users to get the profits and losses easily and also helps the business growth.

### Cons
  - The cons of this vba script is this script won't work or gives the wrong results if the tickers orders are changed in the data set. The tickers order should be same like it mentioned in the script and also we can't compare the years of data. 









