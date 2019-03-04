# TeamProject_Linear_Regression

## Team Name
>### Sigma  

## Tem Member
>### 조현윤, 이상협, 정하연  

## Object 
>### It is to build a model that predicts the total ride duration of taxi trips in New York City
>### It is to predict the duration time for each id
>### For each id in the test set, you must predict the value of the trip duration variable

## Evaluation metric 
> Root Mean Squared Logarithmic Error (RMSLE) is calculated as 
>  
> $$ \epsilon = \sqrt{\frac{1}{n} \sum_{i=1}^n (\log(p_i + 1) - \log(a_i+1))^2 } $$  
>  
>Where:  
> \\(\epsilon\\) is the RMSLE value (score)  
> \\(n\\) is the total number of observations in the (public/private) data set,  
> \\(p_i\\) is your prediction of trip duration, and  
> \\(a_i\\) is the actual trip duration for \\(i\\)  
> \\(\log(x)\\) is the natural logarithm of \\(x\\)  

## Submission File
> submission files should contain two columns : **id & trip_duration. **
> id corresponds to **the column of that id in the test.csv**  
> the file should **contain a header and have the following format : **  
~~~~
id,trip_duration
id00001,978
id00002,978
id00003,978
id00004,978
        .
        .
~~~~  

## Data
> ### Description  
> dataset is based on **the 2016 NYC Yellow Cab trip record data** made available in [Big Query on Google Cloud Platform](https://cloud.google.com/bigquery/public-data/nyc-tlc-trips).  
> The data was originally published by the [NYC Taxi and Limousine Commission(TLC)](http://www.nyc.gov/html/tlc/html/about/trip_record_data.shtml).  
> The data was sampled and cleaned.  
> ### File Descriptions  
> * train.csv : the training dataset  
> * test.csv : the testing dataset  
> * sample_submission.csv : a sample submission file in the correct format  

> ### Data fields  
> * id - a unique identifier for each trip  
> * vendor_id - a code indicating the provider associated with the trip record  
> * pickup_datetime - date and time when the meter was engaged  
> * dropoff_datetime - date and time when the meter was disengaged  
> * passenger_count - the number of passengers in the vehicle (driver entered value)  
> * pickup_longitude - the longitude where the meter was engaged  
> * pickup_latitude - the latitude where the meter was engaged  
> * dropoff_longitude - the longitude where the meter was disengaged  
> * dropoff_latitude - the latitude where the meter was disengaged  
> * store_and_fwd_flag - This flag indicates whether the trip record was held in vehicle memory before sending to the vendor because the vehicle did not have a connection to the server - Y=store and forward; N=not a store and forward trip  
> * trip_duration - duration of the trip in seconds  

## Reference  
> [kaggle Homepage-NewYork City Taxi Trip Duration](https://www.kaggle.com/c/nyc-taxi-trip-duration)  
