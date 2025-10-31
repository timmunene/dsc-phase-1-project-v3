# Aircraft Safety - NTSB
We shall use the provided National Transportation Safety Board (NTSB) (1962 - 2023) civil aviation data to achieve our objectives.

## Objective
- Determine the lowest risk aircraft for a new business endeavor in commercial and private enterprises
- Incorporate information on purchasing and operating aircraft for commercial and private enterprises where available
- Draft actionable insights for new head of aviation division to decide which aircraft to purchase

This NTSB data has information on accidents and incidents involving aircraft from 1962 to 2023. It lists data on injuries, aircraft type, number of engines, purpose of the flight, level of damage, location of the incident, date and weather at the time etc.

## 1. Data Cleaning and Filtering Steps
a. Check for and remove duplicate rows
b. Clean the 'Make' and 'Model' columns
c. Filter based on purpose of flight
d. Filter to retain data collected in the last 20 years
e. Check the injury columns
f. Check the 'Aircraft.damage' column
g. Drop columns that are not relevant to our objectives
h. Check if amateur or professional aircraft.
i. 'Aircraft.damage' column
## 2. Collate and Group injuries data
## 3. Add incident count per aircraft
## 4. Visualisation
### Aircraft type by Total Injuries
### Aircraft Type by Incident Count
### Export Make_Model_Grp to Excel

# Summary
Using the initial 'Aviation_Data.csv' we filtered the data based on the objectives to get a dataframe indicating the injuries relating to a specific aircraft type and the number of incidents per aircraft type.

The Cessna 421, Beech C90A, Bombardier BD100, Bombardier CL-600, Boeing 737 and Cessna 560 have the lowest injury and incident reports and can be termed as the lowest risk aircraft.

We strongly recommend for further analysis using data such as frequency of flights or flight cycles, aircraft capacity once specifics on the business endeavour have been established.
