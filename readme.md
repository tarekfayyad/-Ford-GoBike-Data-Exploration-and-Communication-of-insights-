# Ford GoBike System Data Exploration
## by (Tarek Fayyad)


## Dataset

> Bay Wheels is a regional public bicycle sharing system in California's San Francisco Bay Area. It is operated by Motivate in a partnership with the Metropolitan Transportation Commission and the Bay Area Air Quality Management District. Bay Wheels is 'the first regional and large-scale bicycle sharing system deployed in California and on the West Coast of the United States. It was established as Bay Area Bike Share in August 2013. As of January 2018, the Bay Wheels system had over 2,600 bicycles in 262 stations across San Francisco, East Bay and San Jose.
>In June 2017 the system was officially re-launched as Ford GoBike in a partnership with Ford Motor Company. After Motivate's acquisition by Lyft, the system was renamed to Bay Wheels in June 2019.The system is expected to expand to 7,000 bicycles around 540 stations in San Francisco, Oakland, Berkeley, Emeryville, and San Jose.
>https://en.wikipedia.org/wiki/Bay_Wheels<br><br>
> There are 183412 observation of fordgobike trips in the dataset with 16 featuress (duration_sec, start_time, end_time, start_station_id, start_station_name, start_station_latitude, start_station_longitude, end_station_id, end_station_name, end_station_latitude ,end_station_longitude, bike_id, user_type, member_birth_year, member_gender, bike_share_for_all_trip).<br> <br>
>Out of 16 features:<br>
>* 9 are numerical (duration_sec,start_station_id,start_station_latitude,start_station_longitude,end_station_id,end_station_latitude ,end_station_longitude, bike_id,member_birth_year).<br>    
>* 8 are object type (start_time, end_time, start_station_name, end_station_name,user_type, member_gender, bike_share_for_all_trip).


## Summary of Findings

>Most customer user type have short trip duration that varies from 5 to 25 minutes with distance that varies 0 to 4000 meters.<br>
>Most Subsriber user type have long trip duration that varies from 5 to 35 minutes with distance that varies from 0 to 6000 meters.<br>
>Majorty of users are male.<br>
>Majorty of male user age range from 25 to 35 years old with trip duration up to 35 minutes.<br>
>Majorty of female user age range from 30 to 35 years old with trip duration up to 30 minutes.<br>
>Male user have higher duration trip than female and other.<br>
>There is strong correlation between distance and duration.<br>
>There is no correlation between age and distance, no correlation between age and duration.
>GoBike usage for Subscriber is almost the same regarding hour.<br>
>GoBike usage for customer differ according hour. The most usage is at 3,4,11,13,14 o'clock<br>
>Trip duration for Subscriber is almost the same regarding week day.<br>
>Trip duration for customer is higher than subscriber especially in Saturday and Sunday.


## Key Insights for Presentation


>Relation between trip duration and distance and age : Trip duration has strong correlation with distance and no correlation with age.
>Relation between trip duration and user type and daily hour : Trip duration for Subscriber is almost the same regarding hour, Trip duration for customer differ regarding daily hour.
>Relation between trip duration and user type and week day: Trip duration for Subscriber is almost the same regarding week day, Trip duration for customer is higher in Saturday and Sunday.


## Resources and Analysis Exploring


>https://en.wikipedia.org/wiki/Bay_Wheels<br>
>https://github.com/sozker/Communicate_Data_Findings<br>
>https://github.com/burakgunbatan/UdacityProject---CommunicateDataFindings<br>
>https://github.com/saiogirala/Ford_Bike_Communicating_Findings<br>
>https://github.com/dkhundley/ford-gobike-analysis<br>
>https://github.com/studybug/Ford-GoBike-Data-Findings<br>
>https://github.com/jemc36/Udacity-DAND-DataVisualization-Ford-GoBike<br>
>https://github.com/Lilianasu/Udacity-Project5-DataVisualization<br>
>https://github.com/adipurnamk/Ford-GoBike-System-Data<br>
>https://github.com/adipurnamk/Ford-GoBike-System-Data<br>
>https://github.com/dirkkadijk/Ford-GoBike-Data-Exploration-and-Communication-of-insights<br>
>https://github.com/rishusingh121/fordgobike<br>
>https://github.com/adipurnamk/Ford-GoBike-System-Data/blob/master/slide_deck_fordgobike_2017.ipynb<br>
>https://www.kaggle.com/athana/dand-project4<br>
>https://www.kaggle.com/chirag02/ford-gobike-data-analysis
