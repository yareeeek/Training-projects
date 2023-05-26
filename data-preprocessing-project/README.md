# 1st-training-project
My first training Data Science project

I was provided with a dataset with user and cartographic (automatic) data on ads for the sale of apartments in the Leningrad region. I did an exploratory data analysis with preprocessing.

# Dataset includes:
1. airports_nearest — distance to the nearest airport in meters (m)
2. balcony — number of balconies
3. ceiling_height — ceiling height (m)
4. cityCenters_nearest — distance to city center (m)
5. days_exposition — how many days the ad was posted (from publication to removal)
6. first_day_exposition — publication date
7. floor - just a floor
8. floors_total — total floors in the house
9. is_apartment — boolean
10. kitchen_area — in square meters (m²)
11. last_price — price at the time of removal from publication
12. living_area — in square meters (m²)
13. locality_name
14. open_plan — boolean
15. parks_around3000 — number of parks within a 3 km radius
16. parks_nearest — distance to nearest park (m)
17. ponds_around3000 — number of ponds within a 3 km radius
18. ponds_nearest — distance to nearest pond (m)
19. rooms — number of rooms
20. studio — boolean
21. total_area — total area of the apartment in square meters (m²)
22. total_images — number of photos of the apartment in the ad

# What i did?
Upon receiving the dataset, I got rid of the gaps in the columns, replacing them with zero or median values, changed incorrect data types, eliminated anomalies and implicit duplicates in the names of settlements.

For the convenience of subsequent analysis and visualization, I added new columns with days of the week, months, years, price per square meter. meters, distance to the center in km and floor type.

During the analysis, I described and visualized the various parameters of the displayed ads. I studied how quickly apartments are sold: a "long" ad can be considered a year after being put up for sale. Investigated the dependence of the price on various parameters: the price increases with the growth of the kitchen area, living and total area, and to a lesser extent with the increase in the number of rooms. I found out that among the top 10 settlements in terms of the number of ads, the highest price per square meter is in St. Petersburg, and the lowest in Vyborg. And finally I found that the closer to the center, the more expensive the apartment is.
