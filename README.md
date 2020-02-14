# Comparing Social Mobility in Baltimore and Atlanta
## Household and Income Levels
With the demographics being all genders/ethnicities and the individual's parents being classified as low income, the household and individual income levels in Baltimore and Atlanta are recorded and graphed. 

![Picture1](https://user-images.githubusercontent.com/60996310/74511407-eaa57780-4ed3-11ea-9279-24a298d741a4.png)

![PicAtlanta](https://user-images.githubusercontent.com/60996310/74511140-50ddca80-4ed3-11ea-962b-63f040868712.png)

Since these individuals/households in both cities came from households of lower incomes, judging by these charts, it's conveyed that Atlanta has allowed for more social mobility as the income increments are of much higher value. The more affluent counties have household/individual incomes up to 3.5M in Atlanta compared to the 1.85M in Baltimore county where the wealthiest households/individuals reside. Baltimore's data conveys that there are distinctive socioeconomic differences between counties that correspond to the numerous and noteworthy peaks among the counties with more of the same lower-income individuals, a gap between the rich and poor, which may convey the difficulty of Baltimore residents in climbing the social ladder; Atlanta's chart has fewer distinctive peaks. In both graphs, most of the residents' income levels are near the bottom indicating that most individuals from less fortunate families might well still be struggling. This is important to know as a student because it raises awareness which is a catalyst for change so that poverty doesn't persist in one area generation after generation.  

Source: https://www.opportunityatlas.org/
Article about Atlanta Social Economic Gap: https://www.ajc.com/news/local/atlanta-has-the-worst-income-inequality-the-bloomberg-report-finds/BsUkLHtoLEZEwI504r9oeM/

Orginal Excel files: [AtlHousehold.xlsx](https://github.com/vtran24/comparing-baltimore-atlanta-household-income/files/4203422/AtlHousehold.xlsx)
[AtlIndi.xlsx](https://github.com/vtran24/comparing-baltimore-atlanta-household-income/files/4203423/AtlIndi.xlsx)
[BaltyHousehold.xlsx](https://github.com/vtran24/comparing-baltimore-atlanta-household-income/files/4203425/BaltyHousehold.xlsx)
[BaltyIndi.xlsx](https://github.com/vtran24/comparing-baltimore-atlanta-household-income/files/4203426/BaltyIndi.xlsx)

Excel workbook: [shown_tract_kir_rP_gP_p25.xlsx](https://github.com/vtran24/comparing-baltimore-atlanta-household-income/files/4203410/shown_tract_kir_rP_gP_p25.xlsx)

### ExcelDataSteps
1. Download Data from Atlanta and Baltimore for Individual and Household Income Levels.
2. Put the data of each city on different worksheets.
3. For each city, click on an empty cell space. Use VLOOKUP and use the tract # to match individual income to the corresponding household income in each tract (ie. =VLOOKUP ((E2,A:C, 3, FALSE))
4. Create a pivot chart with the data from each city. Place the name of the county in the "Rows" category and sum of household income along with sum of individual income in "Values" category. 
5. Create a Pivot Chart with the data. Change it to a line graph. Add axis titles and chart titles correspondingly. 
