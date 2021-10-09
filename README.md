# US-Accidents
## US Accidents Dataset
#### Here is the link to the source of my data file: https://www.kaggle.com/sobhanmoosavi/us-accidents

### TABLE OF CONTENTS :

PART I: Introduction

PART II: Data Wrangling

* Data Gathering

* Data Assessing 

* Data Cleaning
PART III: Univariate Exploration

PART IV: Bivariate Exploration

PART V: Multivariate Exploration

### Introduction :

This is a car accident dataset, which covers 48 states of the USA. In this dataset, the records have been collected from 2016 to 2020 using several data providers and multiple APIs provides streaming traffic event datas. Currently there are about 3 million accident records in this dataset and 47 columns.

The following are the dataset columns and its detail describtion :

ID : Unique identifier of the accident record.

Severity : Severity of the accident, a number between 1 to 4, where 1 - very short delay, 2 - short delay, 3 - long delay 4 - very long delay.

Start_Time : starting time of the accident in local zone.

End_Time : Ending time of the accident in local zone.

Start_Lat : Latitude in GPS co-ordinate of start point.

End_Lat : Latitude in GPS co-ordinate of end point.

Start_Lng : Longitude in GPS co-ordinate of start point.

End_Lng : Longitude in GPS co-ordinate of end point.

Distance(mi) : Length of the road, affected by the accident.

Description : Overall description of the accident.

Number : Street number in address field.

Street : Street name in address field.

Side : Side of the street i.e, Right and Left.

City : City in address field.

County : County in address field.

State : State in address field.

Zipcode : Zipcode in address field.

Country : Country in the address field.

Airport_Code : Airport based weather station which is cloaset to the location.

Timezone : Timezone based on the location of the accident.

Weather_Timestamp : Time stamp of the weather observation record.

Temperature(F) : Temperature in Fahrenheit.

Wind_Chill(F) : Wind Chill in Fahrenheit.

Humidity(%) : Humidity in percentage.

Pressure(in) : Air pressure in inches.

Visibility(mi) : Visibility in miles.

Wind_Direction : Shows wind direction.

Wind_Speed(mph) : Wind speed in miles per hour.

Precipitation(in) : Precipitation amount in inches.

Weather_Condition : Shows weather conditions.

Amenity : A POI annotation which indicates presence of amenity in nearby location.

Bump : A POI annotation which indicates presence of bump in nearby location.

Crossing : A POI annotation which indicates presence of crossing in nearby location.

Give_Way : A POI annotation which indicates presence of give-way in nearby location.

Junction : A POI annotation which indicates presence of junction in nearby location.

No_Exit : A POI annotation which indicates presence of no-exit in nearby location.

Railway : A POI annotation which indicates presence of railway in nearby location.

Roundabout : A POI annotation which indicates presence of roundabout in nearby location.

Station : A POI annotation which indicates presence of station in nearby location.

Stop : A POI annotation which indicates presence of stop in nearby location.

Traffic_Claming : A POI annotation which indicates presence of trafficc-claming in nearby location.

Traffic_Signal : A POI annotation which indicates presence of traffic-signal in nearby location.

Turning_Loop : A POI annotation which indicates presence of turning-loop in nearby location.

Sunrise_Sunset : Period of day based on sunrise and sunset.

Civil_Twilight : Period of day based on civil twilight.

Nautical_Twilight : Period of day based on nautical twilight.

Astronomical_Twilight : Period of day based on astronomical twilight.

