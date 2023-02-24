# (Airline Passenger Satisfaction)
## by (Valentine Ezenwanne)


## Dataset

This dataset Airline Passenger Satisfaction contains survey on Customer satisfaction scores from 129,880 airline passengers, including additional information about each passenger, their flight, and type of travel, as well as ther evaluation of different factors like cleanliness, comfort, service, and overall experience.

The dataset can be found in the repository https://www.kaggle.com/datasets/mysarahmadbhat/airline-passenger-satisfaction

The dataset was assessed and quality issues such as 393 missing values and Incorrect datatypes was observed. After cleaning, there are 129,487 satisfaction survey records with 24 features. Most features are categorical variable while 4 features (Age, Flight Distance, Departure Delay, Arrival Delay) are numericals.


## Summary of Findings

In the exploration, I found that the airline passengers are categorized into Returning and First-time customers, of which the Returning Passengers were greater in number. These passengers travelled either for business purposes or personal reasons, of which business travel constitute a greater part of the reasons for the travel. The passengers ply either business, economy or economy plus class, of which the first two constitute the major classes flown. 

The Age of the passengers showed a bimodal distribution, the first peak age distribution is between 22-30 years while the second peak age distribution is between 35-45 years. The median Age of the returning passenger was above 40 with wide age range while for first time passenger, the median age is litte below 30 with small age range and with outliers.

Majority of our returning customer travel longer distance and for business purposes. They ply these long distances using business class. The higher the average flight distance travelled, the more satisfied these passengers are with some of the inflight features such as In-flight Service, In-flight Entertainment, Seat Comfort and Leg Room Service.

The features that contributed to the satisfactions are In-flight Entertainment, Seat Comfort, Leg Room Service, Cleanliness, On-board Service which had high number of satisfactions at high ratings of 4 and 5 and these high number of satisfactions were observed mostly among the passsengers that ply the business class

The features that contributed to the dissatisfaction of the passengers are In-flight Service, Departure and Arrival Time Convenience, In-flight Wifi Service, Food and Drinks, Ease of Online Booking, Check-in Service, Gate Location and Baggage Handling. These dissatisfaction were observed mostly among passengers that ply the Economy class and Economy plus.


## Key Insights for Presentation

For the presentation, i will focus on the categorical variables, Departure and Arrival Time Convenience, In-flight Service, In-flight Wifi Service and In-flight Entertainment, Food and Drinks, Seat Comfort and Leg Room Service which i believe will have strong effect on the overall Satisfaction and Dissatisfaction of the passengers.

I will start by introducing the numerical variable Flight Distance, i will then plot its distribution. Then, i will introduce the categorical variables aforementioned earlier and also plot their distribution.

I will proceed by using barplot to look at how the numerical variable Flight Distance influences the Satisfaction ratings of each of the features, and also i will use a clusterplot to plot each feature against the Satisfaction to find out if the ratings are as a result of satisfaction or dissatisfaction.

I will then summarize by looking at how the satisfaction and each features vary among the type of airline classes