A stylish interactive dashboard of Melbourne Property Market


![melbourne-property](https://github.com/tonCodesData/melbourne-property-auction-report-Excel/assets/124179394/de12a80a-32b5-4d59-afb0-4e3245343a35)


From an dataset consisting of 25478 rows and 24 columns, deatiling properties sold at auction for 2017 and 2018 in Melbourne, Australia, I created a series of visualisations and later used them in constructing an interactive dashboard for exploring the Melourne property market. The users can see key metrics for a selected Council Region and Month.   

The process of making the visualisations: 
1. First to make data easier to work with, I converted the data into a table. 
2. On the first visualisation, I wanted to show the trends for House and Unit sales for each year. 
2.1 In the Melbourne Trends sheet, I created a PivotTable with the data - added Price to Values, Month to Row, and Type to Column. This provided with house and falt sales for each month. 
2.2 by changing the calculation to an Average and Number format to Currency, we get the average unit price for each month by housing type. 
2.3 To visualise I selected the 2D Line PivotChart, turned off gridlines, legend, Field buttons, and changed the vertical axis units to Thousands. Then I selected a line series and formatted to Smoothed Line checkbox. 


