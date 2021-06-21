
# Kickstarting with Excel

The ability to consolidate data points, analyze data and create a cohesive narrative is the ultimate goal of any data analysis. Excel helps us to do these with formulas, slicers and pivot charts. With all these we can aggregate data to create a meaningful reports. 

## Overview of Project

Louise’s is a playwrighter who wants to do a fundraising project campaign "Fever". She has a crowd funding data which we have to organize, sort and analyse to make her project successful.

### Purpose

The Kickstarter data involved in this project has different category, country, goals, backer and dates which decides the outcome(Successful, failed or canceled) of it. So, the purpose of this data analysis is to know how different campaigns fared in relation to their launch dates and their funding goals.


## Analysis and Challenges

As there are more category and items involved, we can do some modifications in the existing data and create new columns for better understanding. For example,

* Applying Filter for a better view
* Calculating the Average and Percentage amounts from Goal and Pledge amounts.
* Dividing the Category into Parent & Sub categories 
* Converting Timestamps to a readable format using formula. 

![Newly created_Columns](https://github.com/saranyadurairaju/module1-kickstarter-analysis/blob/main/Date_Based_chart.png)

### Analysis of Outcomes Based on Launch Date

However we catagorize the data, its difficult to come for a conclusion without visualization. So, we need to use Pivot and other Formulas to have this visualization is needed.

* Using a pivot table, we are comparing the outcomes based on every month as the date plays a important role in campaign. 

* We are slicing the data based on Parent Category and Years to find which category will give more success for Louise.

* With this data, we are using Line chart to compare and visualize the outcomes (successful, failed and canceled).

![date_based_chart](https://github.com/saranyadurairaju/module1-kickstarter-analysis/blob/main/Date_Based_chart.png)

### Analysis of Outcomes Based on Goals

* As Goal is one of the main parameter which decides the Success of the project, we are finding the Percentage of outcomes for different range of Goal amounts.  Then, we can easily compare the percentage of Outcomes in the Goal range with the Line chart.

* Below is the Line chart comparison of Outcomes based on Goals.

![parent_category_chart](https://github.com/saranyadurairaju/module1-kickstarter-analysis/blob/main/Parent_Category_chart.png)

### Challenges and Difficulties Encountered

* Finding which data to compare or analyze is the difficult part of it. But understading the project and visualizing the data properly helps us overcome from this challenge.

* Using the right formulas and charts is little challenging. And Pivot table helps us to compare different categories.

## Results

Below is the Excel worksheet with updated "Kickstarter" data and above charts:

![Kickstarter_Conversions](https://github.com/saranyadurairaju/module1-kickstarter-analysis/blob/main/data-1-1-3-StarterBook.xlsx)

#### The Outcomes based on Launch Date

* Theater category has more successful Outcomes and Total Projects compare to all other categories. 

* It has more successful projects in the month of May, June and July, which means summer vacation is a peak time to do the play.

#### The Outcomes based on Goals
 
  When the goal amount is less than 5000 it has more successful ratio and then between 35000 to 45000. But if we think of a common situation, less 5000 works better always.

#### Limitations of the dataset

  Having the data with Preference of Category and Goals for differnt age limits and types of people (based on Sex, Proffession etc) help us to get more successful outcome. 

#### Other possible tables and/or graphs

- As we have many countries involved in this data, we can do country and category based comparison to find success ratio on each country.

- Some category play can be successful for higher Goal amounts as well. So finding the highest possible goal amounts for each category help Loiuse to collect more funds.

I hope Louise can end up with a Successful fundraising campaign with all of the above data Analysis. Wishing Louise all the very best!
