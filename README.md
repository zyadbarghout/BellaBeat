## BellaBeat
Bellabeat, a high-tech manufacturer of health-focused
products for women. Bellabeat is a successful small company, but they have the potential to become a larger player in the
global smart device market.

Products
# Bellabeat app: The Bellabeat app provides users with health data related to their activity, sleep, stress,
menstrual cycle, and mindfulness habits. This data can help users better understand their current habits and
make healthy decisions. The Bellabeat app connects to their line of smart wellness products.
○ Leaf: Bellabeat’s classic wellness tracker can be worn as a bracelet, necklace, or clip. The Leaf tracker connects
to the Bellabeat app to track activity, sleep, and stress.
# Time: This wellness watch combines the timeless look of a classic timepiece with smart technology to track user
activity, sleep, and stress. The Time watch connects to the Bellabeat app to provide you with insights into your
daily wellness.
# Spring: This is a water bottle that tracks daily water intake using smart technology to ensure that you are
appropriately hydrated throughout the day. The Spring bottle connects to the Bellabeat app to track your
hydration levels.


Approaching this dataset I wanted to put on the user's shoes and live his journey day by day, so the classification here will be according to the weekdays and the hours


Plotting the average steps against the weekdays it was obvious that the users are most active at the Saturdays and Tuesdays and least active at the Lazy Sundays



![alt text](https://github.com/zyadbarghout/BellaBeat-/blob/master/images/avg%20steps%20daily.PNG)


While this was a great insight it reamined unclear when were the users most active among these days and what is the reasoning behind it?

Asking such a question took me to analyze the daily life routine of the users through their steps daily in which it was found that:
The users are most active between 5 pm to 7 pm and also at 12 pm, well great you can recognize there that 5 to 7 are the hours when employees finish their working day so that is logical
and also at 12 pm as this would be the lunch break 

![alt text](https://github.com/zyadbarghout/BellaBeat-/blob/master/images/steps%20avg%20hourly.PNG)

Great! but still we need to go the extra mile here and both validate our hypothesis and search for more insights

So, I went through the steps distribution daily by hours to find that the working days had the 5 to 7 spikes while it was absent in the Saturdays and Sundays confirming our hypothesis there

![alt text](https://github.com/zyadbarghout/BellaBeat-/blob/master/images/steps%20av%20daily%20by%20hours.PNG)

Following this we needed to study further the users' behaviors and their activities according to both minutes and distance
So we found out that the most of the time the users' are spending their time mostly sedentary and when they are doing activities it is mostly light ones


![alt text](https://github.com/zyadbarghout/BellaBeat-/blob/master/images/minutes%20distribution.PNG)


and then when plotting the distance of each activity the light activities were the highest normally as they had the highest minutes and then the very active minutes which came second 

![alt text](https://github.com/zyadbarghout/BellaBeat-/blob/master/images/distance%20distribution.PNG)

So now we have an understanding of the users' weekly journey and now we know how to approach them according to these information.

The Business Reccomendations to each product according to our data:

# Bellabeat app: The Bellabeat app provides users with health data related to their activity, sleep, stress and mind-fullness

We can use the app to let the user program the bellabeat leaf to vibrate when the user is resting for over certain amount of time at certain time frames

We can use the insights that we gained here and send the users notifications through the app at:
# Sundays when the users tend more to be lazy and we can remind them of there goal how close they are to it if they started exercising
# 5 to 7 pm of the working days when the users are most active, we can send them encouraging notifications to elevate their exercising levels
# When they are recorded to be sedentary for overy 10 hours, we can send them notifications to encourage them to do some activities


# Leaf: Bellabeat’s classic wellness tracker can be worn as a bracelet, necklace, or clip. 
The Leaf tracker connects to the Bellabeat app to track activity, sleep, and stress.

# We can use the app to let the user program the bellabeat leaf to vibrate when the user is resting for over certain amount of time at certain time frames

# Time: This wellness watch combines the timeless look of a classic timepiece with smart technology to track user
activity, sleep, and stress. The Time watch connects to the Bellabeat app to provide you with insights into your
daily wellness.

# We can use the watch to recieve the same notification sent by the app and collect more data about the consented users 

# Spring: This is a water bottle that tracks daily water intake using smart technology to ensure that you are
appropriately hydrated throughout the day. 

#The Spring bottle connects to the Bellabeat app to track your hydration levels and reminds you of your hydration goal daily.

## To check the visualizations in [tableau] (https://public.tableau.com/app/profile/zyad3828/viz/BellabeatProjecct/Distancecoveredineachactivitymode#guest=n)
