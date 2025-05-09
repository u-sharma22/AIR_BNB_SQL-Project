# AIR_BNB_SQL-Project
Airbnb's "Hospitality Intelligence Hub" uses MySQL to analyze data on NYC neighborhoods, listing types, prices, and availability. It tracks customer behavior, preferences, and trends, helping Airbnb optimize pricing, improve listings, and enhance customer satisfaction by making data-driven decisions to boost occupancy and operations.

Airbnb – Hospitality Intelligence Hub
 
Description
Airbnb is a leading online marketplace that provides accommodation options across various neighborhoods in New York City and around the globe. To ensure their business operations run smoothly, Airbnb has developed a cutting-edge 'Hospitality Intelligence Hub' that analyzes data from various sources for better insights and trends. By using this tool, Airbnb gains valuable insights into their business operations, which help them make informed, data-driven decisions.
The 'Hospitality Intelligence Hub' uses MySQL to analyze data which contains information on various neighborhoods in New York City, including the types of listings available, the prices of these listings, and their availability. The system tracks trends in customer behavior and preferences, such as frequently booked room types, price trends for specific neighborhoods etc.
With this tool, Airbnb can identify areas for improvement and make changes to their operations to improve customer satisfaction. For example, the 'Hospitality Intelligence Hub' helps Airbnb optimize pricing for different neighborhoods to increase occupancy rates, improve listings based on customer preferences, and enhance the customer experience by identifying areas for improvement.
In our case study on Airbnb's Hospitality Intelligence Hub, we have two tables: 'Listings' and ‘Booking_Details. The ‘Listings' table contains information on the various neighborhoods in New York City, including the types of listings available in each neighborhood. The 'Reviews' table, on the other hand, has information on the prices of these listings, reviews and their availability.
Both the tables, ‘Listings’ and ‘Reviews’ are provided in the form of .csv file.
Description of Listings Table:
·       id: A unique identifier for each listing.
·       name: The name of the listing.
·       host_id: A unique identifier for the host of the listing.
·       host_name: The name of the host.
·       neighbourhood_group: The group of neighborhoods that the listing belongs to.
·       neighbourhood: The name of the neighborhood that the listing belongs to.
·       room_type: The type of room that is being listed (e.g. private room, entire apartment).
Now let's take a closer look at the ‘Booking_Details table description:
·       listing_id: A unique identifier for each listing.
·       price: The nightly price of the listing.
·       minimum_nights: The minimum number of nights that a guest must book in order to stay at the listing.
·       number_of_reviews: The total number of reviews that the listing has received.
·       reviews_per_month: The average number of reviews that the listing receives per month.
·       calculated_host_listings_count: The number of listings that the host has on Airbnb.
·       availability_365: The number of days that the listing is available for booking throughout the year.
Questions:
1.           Import Data from both the .CSV files to create tables, Listings and Booking Details.
2.           Q2 Write a query to show names from Listings table
3.           Write a query to fetch total listings from the listings table
4.           Write a query to fetch total listing_id from the booking_details table
5.           Write a query to fetch host ids from listings table
6.           Write a query to fetch all unique host name from listings table
7.           Write a query to show all unique neighbourhood_group from listings table
8.           Write a query to show all unique neighbourhood from listings table
9.           Write a query to fetch unique room_type from listings tables
10.      Write a query to show all values of Brooklyn & Manhattan from listings tables
11.      Write a query to show maximum price from booking_details table
12.      Write a query to show minimum price fron booking_details table
13.      Write a query to show average price from booking_details table
14.      Write a query to show minimum value of minimum_nights from booking_details table
15.      Write a query to show maximum value of minimum_nights from booking_details table
16.      Write a query to show average availability_365
17.      Write a query to show id , availability_365 and all availability_365 values greater than 300
18.      Write a query to show count of id where price is in between 300 to 400
19.      Write a query to show count of id where minimum_nights spend is less than 5
20.      Write a query to show count where minimum_nights spend is greater than 100
21.      Write a query to show all data of listings & booking_details
22.      Write a query to show host name and price
23.      Write a query to show room_type and price
24.      Write a query to show neighbourhood_group & minimum_nights spend
25.      Write a query to show neighbourhood & availability_365
26.      Write a query to show total price by neighbourhood_group
27.      Write a query to show maximum price by neighbourhood_group
28.      Write a query to show maximum night spend by neighbourhood_group
29.      Write a query to show maximum reviews_per_month spend by neighbourhood
30.      Write a query to show maximum price by room type
31.      Write a query to show average number_of_reviews by room_type
32.      Write a query to show average price by room type
33.      Write a query to show average night spend by room type
 
34.      Write a query to show average price by room type but average price is less than 100
35.      Write a query to show average night by neighbourhood and average_nights is greater than 5
36.      Write a query to show all data from listings where price is greater than 200 using sub-query.
37.      Write a query to show all values from booking_details table where host id is 314941 using sub-query.
38.      Find all pairs of id having the same host id, each pair coming once only.
39.      Write an sql query to show fetch all records that have the term cozy in name
40.      Write an sql query to show price, host id, neighbourhood_group of manhattan neighbourhood_group
41.      Write a query to show id , host name, neighbourhood and price but only for Upper West Side & Williamsburg neighbourhood, also make sure price is greater than 100
42.      Write a query to show id , host name, neighbourhood and price for host name Elise and neighbourhood is Bedford-Stuyvesant
43.      Write a query to show host_name, availability_365,minimum_nights only for 100+ availability_365 and minimum_nights
44.      Write a query to show to fetch id , host_name , number_of_reviews, and reviews_per_month but show only that records where number of reviews are 500+ and review per month is 5+
45.      Write a query to show neighbourhood_group which have most total number of review
46.      Write a query to show host name which have most cheaper total price
47.      Write a query to show host name which have most costly total price
48.      Write a query to show host name which have max price using sub-query
49.      Write a query to show neighbourhood_group where price is less than 100
50.      Write a query to find max price, average availability_365 for each room type and order in ascending by maximum price.

