# python-api-challenge


Application Programming Interface, also known as API, is composed of function that allows a user to access data through some software components. For this week's challenge, we were asked to compose a weather summary of several different cities, and organized the information using scatter plots and linear regression lines. 



Several skills that were used in past challenges were also used for this week's challenge, however, an API key had to be added to the set of skills. An API key is obtained from a website where the desired information is located at, and to eventually derive only the needed information. This is done by having a seperate file with the API key, and later recalling that specific file to get the key. This gets all of the information that this API key has, therefore, dataframes need to be created in order to sort the data based on only what is being looked at. For the purpose of this challenge, we looked at the humidity, cloudiness, latitude, longitude, highest temperature, and windspeed for each city. Scatter plots were created to find the correlation between each of these.  

After finding this data, the data was split into two dataframes, one for northern hemisphere and one for southern hemisphere, where the latitude was used to determine the hemisphere where each city belonged in. Linear regressions were calculated using the statistics command "linregress". It is interesting to see the weather differences between each hemisphere, as well as which factors has the greatest correlation and which ones have the least.   


Although the data that we found in this challenge was helpful, I do believe that it would have been more accurate if we were comparing between continents rather than hemispheres. I think that dividing the data and observing it based on countries will better determine the outliers.

Another thing that I believe should have been added to determine a more accurate reading of the data is adding the lowest temperature of each city. We can have a range of temperatures for each city, and have a better understanding of factors already included, for example, the humidity levels. 

Lastly, having a specific time frame would create the data more accurate. I do not believe that narrowing down the time frame would be a good idea in this case; instead, having weather reports for the past 3-5 months would create a better prediction of the data that we are attempting to read.  


In conclusion, API keys are extremely helpful in attempting to getting to know the full information of a certain topic. The skills used to create graphs from the last homework challenge were also used to organize the data and see the correlation between the different factors for this week's homework challenge. In other words, the skills that have been taught throughout this time will continue to be used in future challenges. Everything is tied together, and the intended audience would be able to benefit from this.
