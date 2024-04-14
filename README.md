## Companies Market Capitalisation Project

### Objectives

The main objectives of this analysis were to find out the following information:

-  The market capitalisations of the Top 10 companies in the world.
-  The total percentage of the number of shares for each market capitalisation category.
-  The number of companies, in the Top 500, that belong to different stock price ranges.
-  The number of companies that belong to each of the G20 countries.

### Data Understanding

The dataset was originally created on 29th January 2024 on www.companiesmarketcap.com and was subsequently made available on Kaggle. The data was downloaded from Kaggle. 

### Visualisations

![image](https://github.com/saemeqamar2024/companies-market-capitalisation/assets/163443584/cf9bd802-7d5a-473d-af9e-00374e4a802b)
![image](https://github.com/saemeqamar2024/companies-market-capitalisation/assets/163443584/36e6ddfb-b0f4-4f2c-8dad-24745b2b9322)
![image](https://github.com/saemeqamar2024/companies-market-capitalisation/assets/163443584/3af066a4-4512-444f-913b-91e1eafe386f)
![image](https://github.com/saemeqamar2024/companies-market-capitalisation/assets/163443584/d924cfab-1266-4dc3-9113-c7c76be185f1)
![image](https://github.com/saemeqamar2024/companies-market-capitalisation/assets/163443584/ff22f66c-c289-4f6f-b16b-6e0a550b287b)

### Technologies Used

Microsoft Excel was used for data cleaning, transformation and analysis.

## Approach Taken

This was a quantitative analysis. Here is a high-level overview of the data cleaning steps taken:

##### Added
  - 1 column for classifying companies by their Market Capitalisation category.
  - Highlighting "Market Capitalisation" figures according to their categories.
  - 1 column for showing the number of shares each company has.

##### Changed
	- "Marketcap" column renamed to "Market Capitalisation".
	- "Country Flag" column renamed to "Country Abbreviation".
  - "Market Capitalisation" column values converted to currency values with 2 decimal places.
  - Rounding all "Stock prices" to 2 decimal places.
  - Abbreviated/short-named countries renamed to their respective full names.

##### Removed
	- "Blanks" from "Country Name".
	- "Company Codes" column (not useful for analysis).
	- "NA" values from "Market Capitalisation" column.
	- "$0 M" values from "Market Capitalisation" column.
	- Duplicate company names.
	- "NA" values from "Stock Prices".
	- Stock price values that are less than $0.01.
	- "Origin Flag" column (not useful for analysis).

##### Fixed
  - Entered "Germany" as country for the company called "Ceconomy".















