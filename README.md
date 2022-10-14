
# Flight - Can We Really Explain Them
For many years, the New York region has struggled greatly with flight delays. Although several factors have contributed to this issue, the three main causes are a constrained airspace, a capacity issue at the three major airports in the area, and the ongoing expansion in air traffic. Using flight limits (or caps) under the High-Density Rule, the FAA first tried to control aircraft delays at LaGuardia, Newark, and Kennedy in 19702. However, such limits were gradually phased off between 2000 and 2007. 3 The phase-out resulted in record levels of flight delays for the New York region, despite having observable benefits including lower air rates and service to new markets due to increasing competition. To stop delays from worsening, the FAA reinstated flying limitations in 2008. However, despite record delays, these new caps haven't made much of a dent in New York's delays since the FAA based them on the airports' operating levels from 2007 and didn't set an on-time performance goal. The FAA will need to revaluate flight caps in order to make them more effective in avoiding delays from once again reaching record levels. They should be based on reasonable airport operating circumstances, air carrier scheduling procedures, and an acceptable rate of delay.
This has give us a chance to make this study using the stats shared with us.


## Authors

- [@mosesmwale](https://github.com/mosesmwale)


## Skills
- Exploratory visualizations with matplotlib and seaborn libraries: countplot, hist, scatter, pairplot, boxplot, facetgrid, barplot, pointplot.
## Dataset
> This dataset is from Bureau of Transportation Statistics. It tracks the on time performance of domestic flights operated by large air carriers. The dataset is for each year and can be downloaded directly from their website. The description is posted on their website in detail.
>This data set is one of the selected by Udacity.

## Findings
In this exploration I investigate the relation between all variables. I found some things that I expected such as a huge correlation between Departure Delay and Arrival Delay or Distance and Elapsed Time. There are 2 main paths in this exploration:
- What are the main causes of cancellations, and how do they connect to the origin airport or month (or not)?
- How delays affect (or do not affect) other factors like the airline, the airport of departure, the route (the combination of the airports of departure and arrival), the time, the date, and the amount of time that has passed.
According to my research, delays are distributed bimodally, with the majority of them occurring between 20 and 15 minutes for severe delays. The delays are somewhat correlated with the route, airline, and airport. The airlines with the most flights should have the most delays, yet this is not the case. Delays have no relationship to elapsed time or departure time. We see that there are some combinations where the delays are significantly larger and some combinations where they are significantly lower when we combine Day of Week and Month. When we mix airline and airport, the same thing occurs.
2% or fewer flights were canceled. Weather is the main cause of cancellations, followed by carriers and the national air system. This ranking remains the same when we search by airport, yet some airports have incredibly identical counts for two or three different factors. There are some routes in particular that have more cancellations than others. There are various differences when we look by month, but the trend remains the same.

## Explantion Insights
I concentrate on the elements that have a stronger connection to delays for the presentation. I first show how delays are distributed before identifying the airlines with the highest mean delays. Then I keep only the airports with the most planes departing, and I plot what the mean delays are for those airports. Finally, I demonstrate how the combination of Month and Weekday affects the mean delays. 

## files To be submitted
-Flights_Explainatory_Presentation.ipynb
-Flights_Explainatory_Presentation.slides.html
-Flights_Exploratory_Data_Analysis.html
-Flights_Exploratory_Data_Analysis.ipynb


## Challenges
I wanted so much to explore like 5 years down dates. But my computer couldnt handle the process and I only ended up to explore 2 yesr. this was a bit faster and helped me progress. 