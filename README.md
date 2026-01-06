# Crime LA EDA

## Project Instructions

Explore the `crimes.csv` dataset and use your findings to answer the following questions:

-   Which hour has the highest frequency of crimes? Store as an integer variable called `peak_crime_hour`.
-   Which area has the largest frequency of night crimes (crimes committed between 10pm and 3:59am)? Save as a string variable called `peak_night_crime_location`.
-   Identify the number of crimes committed against victims of different age groups. Save as a pandas Series called `victim_ages`, with age group labels `"0-17"`, `"18-25"`, `"26-34"`, `"35-44"`, `"45-54"`, `"55-64"`, and `"65+"` as the index and the frequency of crimes as the values.

## How to approach the project

1. Finding the frequencies of crimes by the hour of occurrence
2. Identifying the area with the most night crime
3. Crimes by age group

### Steps to complete

1. Finding the frequencies of crimes by the hour of occurrence
You can extract the hours from the relevant column, convert it to integer data type, and plot the frequencies.
#### Extracting the hours
#### Plotting the frequencies
#### Storing the hour as a variable

2. Identifying the area with the most night crime
You'll need to filter the data for the relevant hours and count the number of crimes by area.
#### Subsetting for night hours
#### Counting crime by area

3. Crimes by age group
Bin and label victim age into the provided groups, then produce a pandas Series detailing how many crimes were committed against each age group.
#### Creating bins and labels
#### Adding a new column to the crimes DataFrame containing binned age bracket values
#### Counting crimes by victim age group

    