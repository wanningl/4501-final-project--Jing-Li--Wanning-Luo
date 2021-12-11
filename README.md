# 4501-final-project--Jing-Li--Wanning-Luo
4501 final project
1. Our group name: Project Group 22
2. Group member: Jing Li, Wanning Luo [jl5774, wl2826]
  Section: 001
3. Description:

Top 10:

In this jupyter notebook file, we analyzed 10 of the most frequently reasons why people living in ZIP code 10019 call 311. 

To be specific, we first choose all the data with the ZIP code of 10019, and then we filtered all types of complaint in the area of Zip code 10019. After that, we counted the total times of each reason of calling 311 in zip code 10019 and sorted those counts in descending order by number of incidents. At last, we selected the top 10 reasons (which is complaint type in our original data) of people living in ZIP code 10019 call 311, and we displayed the data as a Python variable called top10 in the type of pandas.Series.

As a result, we found that the top 10 reasons (in order) of calling 311 are: Noise - Street/Sidewalk (1299 times), Noise - Residential (1144 times), Homeless Person Assistance (1116 times), Noise (1066 times), Illegal Parking (998 times), HEAT/HOT WATER (866 times), Noise - Commercial (811 times), Non-Emergency Police Matter (776 times), Homeless Street Condition (658 times), Non-Compliance with Phased Reopening (620 times).

Parking:  

In this project, we analyze whether illegal parking incidents are a larger fraction of total 311 incidents in your ZIP code than they are in general. Specifically, we first compute the total number of parking incidents in ZIP code 10019, and then we count the total number of all incidents. Finally, we analyze whether the fraction of zip code 10019 is greater than the total fraction of parking incidents across all ZIP codes. We show our result in the form of a single bool called ‘higher_parking_proportion’ which is True if the fraction of illegal parking in area of zip code 10019 is larger than the total fraction of parking incidents across all ZIP codes, and False otherwise.

At last, we found the result of the bool variable ‘higher_parking_proportion’ is false, which means that fraction of illegal parking in area of zip code 10019 is smaller than the total fraction of parking incidents across all ZIP codes.
