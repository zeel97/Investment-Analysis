# Investment Analysis

### Business Objective:
Spark Funds is an asset management company. They basically invest their clients’ funds into different securities based on the financial objectives. The objective of the analysis is to identify possible areas in which Spark funds can invest in based on their objectives. In case of Spark funds their objectives are:
1. Funds to invest would be between the range of $5 million to $15 million
2. Invest in English Speaking Countries due to ease of communication

For this purpose 3 major factors are identified:
1. Suitable funding type which fits the budget
2. Top English speaking countries, with maximum investments
3. Top sectors to invest in

### Model Development
1. Pre-Processing
  * Merge the 2 two data frames so that all variables (columns) in the companies frame are added to the rounds2 data frame. The final dataset includes the company names and respective details pertaining to the fundings
  * Data Cleaning
    1. Remove the special characters from the dataframe
    2. Lower case the permalinks, company_permalinks, category_list, category
    3. Mapping, replace 0 with na for the categories
2. Data Analysis:
  1. Identify the right funding type
  2. Identify Top 3 English Speaking Countries
  3. Allocate the Primary Sectors of the companies to 8 Main Sectors
  4. Identify Top 3 Sectors

### Analysis

**Funding Type**

There are numerous options for funding such as venture, seed, angel, private equity. The funding type and amount largely depends on the stage of the startup. 
The box plot below shows the investments across 3 main funding types. 
It is seen that, the only mean that falls into Spark Funds’ budget range of $5 million and $15 million is Venture. 
The other 2 funding types also have the certain values within the range, but their mean value is either above or below the budget.
The clearly indicates that Venture Funding is the ideal Funding Type for Spark Funds
![Funding-Type](https://github.com/zeel97/Investment-Analysis/blob/master/Funding_Type.png)

**Top Countries**

Bar Plot below shows the countries that have attracted the highest number of venture fundings within the budget.
Investing in an English-Speaking country is suitable due to ease of communication. 
For this purpose the ideal countries for Spark Funds would be USA that has an extremely high number of investments as compared to any other country.
Following that there is United Kingdom. 
The country with the 3rd highest number of investments is China. Since it is a Non-English speaking country, Canada would be a better option for Spark Funds
![Top-Countries](https://github.com/zeel97/Investment-Analysis/blob/master/Top_Countries.png)

**Main Sectors**

Bar Graph below shows the break down of the Top 3 sectors across each of the Top 3 countries. 
The graph shows that the main sectors that are popular currently in these countries are: 
Cleantech/ Semiconductors
Social, Finance, Analytics, Advertising,
Others
If we look closely, the number of investments in Cleantech/Semiconductors is consistently high, along with Others. 
Social, Finance,Analytics, and Ads has lesser funding as compared to the other 2 sectors in Canada. 
Considering this, and the fact that Others appears to be a more diverse sector, I believe that Cleantech. Semiconductors would be a great sector to invest in.
![Main-Sectors](https://github.com/zeel97/Investment-Analysis/blob/master/Top_Sectors.png)

Note: This was a Team Project
