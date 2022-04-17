# Customer-Profitability-Data-Visualisation
This is a data visualization and analysis with power BI for customer profitability dataset by http://obvience.com/

# Aim of the Project
The Customer Profitability sample contains a dashboard, report, and dataset for a company that manufactures marketing materials.
This dataset is taken from Obvience to see key metrics about a CFO's five business unit managers (executives), products, customers, and gross margins (GM). At a glance, they can see what factors are impacting profitability.
The dataset: https://docs.google.com/spreadsheets/d/1BOpvNOj4Hhp9gZTXj-N6G7nIyd7uVp-g/edit?usp=sharing&ouid=112122185795348101882&rtpof=true&sd=true

# Entities
This analysis contains 9 entity (table) and every table has to attribute.

state
Attribute: StateCode, State, Region
executive
Attribute: ID, Name, Img
industry
Attribute: ID, Industry, Image
customer
Attribute: Customer, Name, City, Postal Code, State, Industry ID, Country/Region
product
Attribute: Product Key, Product
scenario
Attribute: Scenario Key, Scenario
date
Attribute: YearPeriod, Year, Period, Date, Month, QtrID, Qtr
bu
Attribute: BU Key, BU, Division, Executive_id
factsales
Attribute: YearPeriod, Customer Key, Product Key, BU Key, Scenario Key, Revenue, Material Costs, Labor Costs Variable, Taxes, Rev for Exp Travel, Travel Expenses, Cost Third Party, Subscription Revenue
We make the data model from the 9 entity. Just drag every Primary Key of the entity in power pivot or power bi data model
customer-profitability
![image](https://user-images.githubusercontent.com/101447005/163392693-a1a7501d-e2de-49c3-b502-2cffa6ad8f89.png)

# Analytical Aspects
- Team Scorecard:
It focuses on the performance of the five managers and their books of business.
It compared the executives' performance for different months along with the progress in revenue generation by them individually and as a whole.
<img width="579" alt="image" src="https://user-images.githubusercontent.com/101447005/163394981-e746789b-4149-4cff-a789-4fa6ed0518e2.png">

- Industry Margin Analysis:
It provides a way to analyze the profitability compared to what's happening in the entire industry.
It looks at gross margin for the entire industry, broken down by segment. The CFO uses this page to compare company and business unit metrics to industry metrics to help them explain trends and profitability.
<img width="578" alt="image" src="https://user-images.githubusercontent.com/101447005/163395099-edea7b1f-9e74-4809-bddf-f6855d233590.png">

# Credits
Made by Shreya Saini, Manisha Singh and Sakshi Chaudhary as part of evaluation for Computing Tools Workshop.
