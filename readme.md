# Data Visualization Project - Ford GoBike sharing dataset

## Introduction

The data is downloaded from *https://www.fordgobike.com/system-data*. The data is from year 2017 to 2018.

The data contained 2383421 entries or rows and 17 columns which are:

- Trip Duration (seconds)
- Start Time and Date
- End Time and Date
- Start Station ID
- Start Station Name
- Start Station Latitude
- Start Station Longitude
- End Station ID
- End Station Name
- End Station Latitude
- End Station Longitude
- Bike ID
- User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)
- Member_birth_year        
- Member_gender             
- Bike_share_for_all_trip  

During the entire analysis I created some more columns to gather further insights and explore the data more properly

No outliers have been removed during the process

## Summary of Findings

### Findings ( Exploratory Analysis) :

- There are 390637 Customers who make up approximately 16% of all users


- There are 1992784 Subscribers who make up approximately 84% of all users


- There are 330023 Females who make up 25% of all users.


- There are 955017 Males who make up 73.5% of all users.


- Out of the customers:
    - Female           32.45 %
    - Male             65.55 %
    - Other            2.00 %



- Out of the Subscribers
    - Female           24.48 %
    - Male             74.03 %
    - Other             1.47%


- The average age of all the users is around 35


- The youngest user is 18 years old


- The oldest user is 137 years old


- Weekdays are far more popular for renting a bike than Weekends
    - Tuesday, Wednesday and Thursday are the days of the week during which most bikes are rented
    - Saturday and Sunday are the days of the week during which least bikes are rented


- Almost an equal number of bikes are rented during the mornings and afternoons while the number is almost halved during the night


- Fall months see the most bikes being rented (Jul, Aug, Sept,Oct) while spring sees the least (Jan, Feb, Mar)


- The 10 most popular stations are:
    - San Francisco Ferry Building (Harry Bridges Plaza)           
    - San Francisco Caltrain Station 2  (Townsend St at 4th St)    
    - San Francisco Caltrain (Townsend St at 4th St)               
    - The Embarcadero at Sansome St                                
    - Market St at 10th St                                         
    - Berry St at 4th St                                           
    - Montgomery St BART Station (Market St at 2nd St)             
    - Powell St BART Station (Market St at 4th St)                 
    - Steuart St at Market St                                      
    - Howard St at Beale St    


- For the 10 most popular stations:
    - Subscribers >> Customers as seen generally
    - Weekdays are far more popular for renting a bike than Weekends as seen generally
    - Afternoons are more popular for renting a bike than Mornings which is different to what is observed generally
    - On weekdays, the count for number of bikes rented in morning is higher followed by afternoon and then night.
    - On weekends, the count for number of bikes rented is highest in the afternoon
    - Median duration for each station is at around 600-700 seconds


- The average duration of trip for Customers (35 minutes) is far more than that for Subscribers (12-13 minutes)


- The average duration of trip for all months is approximately the same


- The average duration of trip is shorter on weekdays than on weekends 


### Interesting Insights (Explanatory Analysis) :

- Even though almost an equal number of bikes are rented during mornings and afternoons, when this data is narrowed down to only the ten most popular stations, it is found that the number of rentals during the mornings are far more than the number of rentals during the afternoons. This indicate that in other stations, most bikes are rented during afternoons.


- Even though the number of trips on Weekdays are far greater than on Weekends, the average duration for Weekdays is more.


- There is a steep decline in the duration of travel for customers from April to May. This can be probably accounted to the fact that it summer and people cannot ride a bike for so long. Interestingly, there is an increase in the average duration from April to May for Subscribers. This makes logical sense since Subscribers as previously seen are huge in number and rent a bike only for shorter durations hence shorter distances. Hence, the impact of weather on such distances can be neglected and hence, the increase.   


### Multivariate Analyses Output:

- **Customers V/s Subscribers Bike Trends by Age ,Weekdays, Hours**
    
    
    - Customers generally use bikes on Weekends. But there is still a good proportion of Customers using bikes on Weekdays. It is just that the use during Weekends is more than tha use during Weekdays 
   
   
   - Their primary use is on Weekends for recreation purposes (probably) from around 10 am to 7 pm.
   
   
   - On Weekdays their use is most during 8 am to 9 am and 4pm to 6pm.
   
   
   - Interestingly there is no contrasting difference among different age groups. All age groups show similar traits which are mentioned above
   
   
   - Subscribers use bikes primarily during Weekdays as compared to Customers who use it during Weekends primarily.
   
   
   - The peak hours of usage during Weekdays is from 7 am to 9 am and from 4 pm to 6pm. There are hardly any Subscribers who use bikes during the weekends.
   
   
   - This can lead to an explanation that Subscribers primary use of bikes is to commute to and fro to their place of work
   
   
   - Even here, there is no contrasting difference between traits of different age groups
    


- **Males V/s Females  Bike Trends by Age ,Weekdays, Hours**
    
    
- All males primarily use bikes on Weekends. 
    
    
    - For 20-40 year old males:
        - Primary use is on Weekdays from around 7 am to 9 am and 4pm to 7pm. 
        - This is very similar to Customers as seen in previous analysis
    
    
    - For 40-50 year old males:
        - On Weekdays their use is most during 7 am to 9 am and 3pm to 6pm.
        - There are hardly any 40-50 year old males who rent bikes on weekends
    
    
- All  females primarily use bikes on Weekends. But the thing to note here is that on weekends, females ride bikes more than males. 
    
    
    - For 20-40 year old females:
        - Their primary use is on Weekdays from around 7 am to 9 am and 4pm to 7pm. 
        - This is very similar to Customers and Males as seen in previous analyses
        - Use on weekends is more than counterpart males
    
    
    - For 40-50 year old females:
        - On Weekdays their use is most during 7 am to 9 am and 4pm to 7pm.
        - On Weekends their use is far more in comparison to counterpart males.


```python

```
