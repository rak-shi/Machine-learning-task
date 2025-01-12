# Machine-learning-task
# US-Accident to predict accident severity
This project aims to analyze the provided dataset to discover insights that can be visually expressed through the data. The specific objectives include:  Clean and organize the data to ensure consistency and integrity of information.
# About this project: ¶
This project aims to analyze the provided dataset to discover insights that can be visually expressed through the data. The specific objectives include:

Clean and organize the data to ensure consistency and integrity of information.
Conduct exploratory data analysis to identify patterns, trends, and potential anomalies.
Validate correlations between the number of accidents and weather conditions through statistical analysis and visualization techniques.
Graphically represent findings creatively and effectively to clearly communicate conclusions derived from data analysis.

# Data Overview:-
We will first discuss about each attribute and discuss what it stands for:
ID:- A unique identifier for each accident.
Source:- The source which reported the accident.
TMC:- It is Traffic Messagen Channel which providea more detailed description of the event.
Severity:- The level of impact of the accident. 1 being the lowest and 4 being the highest.
Start_Time:- Shows start time of the accident in local time zone.
End_Time:- Shows end time of the accident in local time zone.
Start_Lat:- Shows latitude in GPS coordinate of the start point.
Start_Lng:- Shows longitude in GPS coordinate of the start point.
End_Lat:- Shows latitude in GPS coordinate of the end point.
End_Lng:- Shows longitude in GPS coordinate of the end point.
Distance(mi)-: The length of the road extent affected by the accident.
Description:- The description of the accident.
Number:- Street Number
Street:- Street Name
Side:- Relative side of the address field.
City:- Name of the City.
County:- Name of the county.
State:- Name of the state.
Zipcode:- Zipcode of the address
Country:- Name of the country
Timezone:- Timezone of the location where accident occurred
Airport_Code:- Denotes an airport-based weather station which is the closest one to location of the accident.
Weather_Timestamp:- Shows the time-stamp of weather observation record
Temperature(F) :- Temperature in Fahrenheit
Wind_Chill(F):- Wind chill in Fahrenheit
Humidity(%):- Humidity in percentage
Pressure(in):- Air pressure in inches
Visibility(mi):- Visibilty in miles.
Wind_Direction:- Wind direction
Wind_Speed(mph):- Wind speed in miles per hour.
Precipitation(in): -Precipitation in inches.
Weather_Condition: Shows what was the weather that day, i.e., if it was rainy, sunny, etc.
Amenity:- A Point-Of-Interest (POI) annotation which indicates presence of amenity in a nearby location.
Bump: Tells whether there was any bump on the road.
Crossing:- Tells whether there was any corssing on the road.
Give_Way:- Tells whether there was any give-way sign on the road.
Junction:- Tells whether ther was any junction present.
No_Exit:- Tells whether there was any no-exit sign on the road.
Railway:- Tells whether ther was any railway present nearby.
Roundabout:- Tells whether ther was any roundabout present nearby.
Station:- Tells whether there was any sytation present.
Stop:- Tells whether there was any Stop sign on the road.
Traffic_Calming:- Tells whether ther was any Traffic-calming means present nearby.
Traffic_Signal:- Tells whether there was any taffic signal nearby.
Turning_Loop:- Tells whether there was any turning loop nearby.
Sunrise_Sunset::- Tells us the period of the day based on sunrise or suset.
Civil_Twilight:- Tells us the period of the day based on civil twilight.
Nautical_Twilight:- Tells us the period of the day based on nautical twilight.
Astronomical_Twilight:- Tells us the period of the day based on astrnomical twilight.

# About the Dataset: ¶
The dataset is a compilation of automobile accidents nationwide covering 49 states of the USA. Data were collected from February 2016 to March 2023 using multiple APIs providing real-time traffic incident data. These APIs transmit traffic data captured by various entities including US and state transportation departments, law enforcement agencies, traffic cameras, and sensors within road networks. The dataset currently comprises approximately 7.7 million accident records.

# Data Analysis and Visualization
Once the data is cleaned and prepped for analysis, we take some of the columns and apply statistical methods to see the underlying picture come to the surface. The following columns have been analyzed in this project-

State
City
Start Time
Temperature
Weather Condition
Visibility
Crossing
Traffic Signal
Bump

# Loading the Data¶
This section entails importing the dataset from a CSV file using the Pandas library. The necessary libraries will be imported, and the first 5 rows of the dataset will be visualized.
Data Information
This section explores the dataset US_Accidents, which contains information about various attributes related to car accidents in the US. This includes details like the accident severity, location coordinates, weather conditions, and road features such as crossings and junctions. They've inspected the dataset's columns, checked for missing values, and provided descriptive statistics to understand the numerical features' distributions and characteristics.
# Data Cleaning¶
In this section the missingno library is utilized to visualize missing values in their dataset US_Accidents. After identifying columns with missing data, the percentage of missing values for each column is calculated and dropped those with more than 25% missing data. Additionally, Columns not relevant to the analysis are dropped and removed rows with any remaining missing values.
Exploratory Analysis and Visualization¶¶
In this section, various perspectives are explored. Data analysis includes location-based examination, date-related insights, study of atmospheric factors' impact, and analysis based on traffic characteristics.

# Analysis By Location
This section initially examines the cities and states with the highest accident rates. Following that, a detailed analysis is conducted on the top three states with the most accidents. The primary cities are identified, along with their percentage relative to the rest of the state.

