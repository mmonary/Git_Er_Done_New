# Git_Er_Done_Project_1
## Flight Delays in America: An Analysis
Group 5 Data class: Mike, Emily, Nathir, Masoud

### Who we are:
Our team is tasked with analyzing flight data in the United States to determine

### Gathering :
The dataset was gathered from Kaggle
Contents include information on the various airlines, airports, and delay times
Over 5 million rows of data provided

### leaning
Standardizing and formatting data: renamed original columns to be consistent across the csv files
Identifying missing values: used the “fillna” function to replace Nan with zeros

### Organizing
Sorting in numeric order
Structuring data into various dataframes
Writing proper code comments for each segment 

### Why the delay?
The 2015 U.S. flight data indicated five types of flight delays:

Airline Delay- maintenance issues, crew scheduling problems, or other factors directly related to the operations of the airline.
Security Delay- due to enhanced security screenings, security incidents, or other security-related issues.
Air System Delay- air traffic congestion, air traffic control communication problems, or technical issues affecting the air traffic control system.
Weather Delay- adverse weather conditions that affect flight operations.
Late Aircraft Delay- due to late arrival of the aircraft scheduled for a particular flight. 

### Airline Efficiency  
We calculated the average delay for each airline in our dataframe by using a groupby function and applying the mean aggregation method
Southwest Airlines was the most efficient carrier, with their average delay per flight being 24 minutes
The least efficient carrier with the longest delays on average was SkyWest, with an average 49 minutes per flight


