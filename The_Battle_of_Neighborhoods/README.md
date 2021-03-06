# The Battle of Neighbourhoods

[Applied Data Science Capstone](https://www.coursera.org/learn/applied-data-science-capstone/). Coursera. IBM.

# Analyzing Medical Facilities in New York City Neighbourhoods

# Introduction/Business Problem

Since 2020, pandemics change many things in our lives, everything would be different especially if it is related to health and medicine.

For anyone that has a plan to move to the new city, one of the top questions that would be searched is how far the place from the medical facilities and what type of medical facilities is available in that neighbourhoods.

Through this capstone project, I will be analyzing medical venues in the neighbourhoods of New York City, with the support information from the Foursquare data.

This project would be valuable for anyone that lives and work (also for anyone that plans to be lived or worked) in the neighbourhoods of New York City.

# Data

Here's the data which been used in this capstone project.

*   New York City Boroughs and Neighbourhoods data. The data were already available through the course.

*   Foursquare API explore endpoint to get medical venues for every borough listed on New York City dataset.

Note that Foursquare data for [medical categories](https://developer.foursquare.com/docs/build-with-foursquare/categories/) have limitations if we want to get the venues related to the neighbourhoods in the New York City data. So the data exploration starts from the boroughs level to get the venues and after the collection is finished then join the data to the nearest neighbour with the minimum distance calculation.


