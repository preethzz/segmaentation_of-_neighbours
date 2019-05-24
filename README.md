# segmentation_of_neighbours

A hotelier wants to open an Indian Restaurant in Manhattan,New York. The success of any restaurant depends on multiple factors like location, menu, interior, consistency in taste and many other. hotelier approached us to help him to find a perfect location and menu for his restaurant.

Using New York Neighborhood data and foursquare api we could find the neighborhood details, restaurant ratings and menu of each restaurant.We plan to find neighborhoods where there is good Indian restaurant and get the characteristics of that neighborhood using data analysis. Then we need to find neighborhoods with same character but with less Indian restaurant presence.

Using menu option in foursquare api fetch all the menu from each restaurant and find the common items in best rating restaurant. we could get an idea of what people like to have or what kind of food is more popular.

Using K mean clustering cluster those restaurants into groups according to the menu, price and ratings. it will help us to get a view among the restaurants.

Data
1.From NYU Spatial Repository data feed we get New York Borough and neighborhoods data.

2.Using geopy package we could get, geo location like latitude and longitude of each location

3.from foursquare api we can get, 
3.1. Restaurant Names 
3.2. Id 
3.3. location 
3.4. ratings 
3.5. menu
