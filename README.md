## Overview
Exploring City Bike data from New York to see if there are any general patterns that support adding City Bikes to Iowa. Using Tableua for data visualizations and Python for some data manipulation.

## Results
[https://public.tableau.com/app/profile/nathaniel.meyer/viz/CityBike_16352734882480/CityBikeStory](Link to Dashboard)

The first page of the story shows filterable line-graphs that show how long the bikes were checked out. The top graph is for all users (subscribers or not) with a filter for the how long (in hours) the bike was checked out. As you can see, the almost all rides are under an hour, with over half lasting under 30 minutes. The bottom graph splits the graph above by gender, and has two filters: 1- length of trip (in hours), and 2- gender. This shows that most of the users are male.

The second page shows a heatmap of the time of day the bikes are used. Monday through Friday display a similar pattern of high usage around commute hours (6am-9am, and 4pm-7pm). Saturday and Sunday are used most often between 9am and 7pm with a fairly even distribution of those times. Page three is also a heatmap but adds a breakdown for gender that can be filtered. Unknown has very few rides but they are mostly on the weekends. Male and Female follow the same patterns individualy that the heatmap for all people, but again, more males appear to be using the bikes.

Page four has a heatmap breaking down each user type (subscriber vs customer) by the gender and day of trip. The darkest colors are found in the subscriber section, with males riding more bikes than females and unknown. There are very few Unknown gender subscribers compared to Unknown gender customers. Male and Female follow the opposite pattern with more subscribers than customers.

The last two pages are heat maps of the starting location and ending location of the rides respectively. The first shows the starting points with darker and bigger circles corresponding to the number of such rides. The majority of the rides are loacted in Manhattan and are quite likely related to tourism. The second heat map with the ending location shows a nearly-identical image as the first.


## Summary
As the first page of the story shows, most bike rides take less than an hour, with a right-skewed distribution centered on 5 minutes. As the weekday heatmap showed, there is a M-F pattern where the usage is mostly around commute times. Future analysis would need to be done to combine the two and determine the share of riders using the bikes to commute to and from work. That analysis could then be used to compare the expected demand in Iowa during the work-week. If there is enough demand, then maybe the bike sharing app could work there. However, Iowa and New Yok have very different layouts, and it is likely that Iowa would have a longer average trip compared to NY. So, further analysis would need to be done on company profitability depending on the length of the rides.

One big thing not explored here is the age of the users - how old are the people using the bikes? Which age group (say in 5 year bands) make the company the most amount of money? Do young people without a car take longer rides that make the company lots of money?

Over half of the people riding City Bikes (in the data provided - August 2019 NYC) were males, and the share of subscribers was dominated more by males. If I was doing more research, I would look at the gender distributions of NY vs Iowa. 

Lastly, the data used was from one month in one year in one city - August 2019, New York. The weather plays a factor in demand for the bikes, so basing the analysis solely on a summer month is not smart. Further research would look into season rides and have a way of accounting for the weather's impact.
