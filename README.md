# Driver-acceptance-of-coupon
Using panda and seaborn statistical and visualization techniques to analyze a sample dataset provided

In this assignment, we were tasked on analyzing a wide sample of dataset that comprised of different attributes of drivers that have been offered various types of coupons and how the distance and characteristic of a coupon leads up to a driver accepting or rejecting the coupon.
The Driver characteristics is divided into 13 attributes:
* User Attributes (Number and Category of unique Values):
1.	gender ( 2 )  ['Female' 'Male']
2.	age ( 8 )  ['21' '46' '26' '31' '41' '50plus' '36' 'below21']
3.	maritalStatus ( 5 )  ['Unmarried partner' 'Single' 'Married partner' 'Divorced' 'Widowed']
4.	has_children ( 2 )  [1 0]
5.	education ( 6 )  ['Some college - no degree' 'Bachelors degree' 'Associates degree'  'High School Graduate' 'Graduate degree (Masters or Doctorate)'  'Some High School']
6.	occupation ( 25 )  ['Unemployed' 'Architecture & Engineering' 'Student'  'Education&Training&Library' 'Healthcare Support'  'Healthcare Practitioners & Technical' 'Sales & Related' 'Management'  'Arts Design Entertainment Sports & Media' 'Computer & Mathematical'  'Life Physical Social Science' 'Personal Care & Service'  'Community & Social Services' 'Office & Administrative Support'  'Construction & Extraction' 'Legal' 'Retired'  'Installation Maintenance & Repair' 'Transportation & Material Moving'  'Business & Financial' 'Protective Service'  'Food Preparation & Serving Related' 'Production Occupations'  'Building & Grounds Cleaning & Maintenance', 'Farming Fishing & Forestry']
7.	income ( 9 )  ['$37500 - $49999' '$62500 - $74999' '$12500 - $24999' '$75000 - $87499'  '$50000 - $62499' '$25000 - $37499' '$100000 or More' '$87500 - $99999'  'Less than $12500']
8.	car ( 6 )  [nan 'Scooter and motorcycle' 'crossover' 'Mazda5' 'do not drive'  'Car that is too old to install Onstar :D']
9.	Bar ( 6 )  ['never' 'less1' '1~3' 'gt8' nan '4~8']
10.	CoffeeHouse ( 6 )  ['never' 'less1' '4~8' '1~3' 'gt8' nan]
11.	CarryAway ( 6 )  [nan '4~8' '1~3' 'gt8' 'less1' 'never']
12.	RestaurantLessThan20 ( 6 )  ['4~8' '1~3' 'less1' 'gt8' nan 'never']
13.	Restaurant20To50 ( 6 )  ['1~3' 'less1' 'never' 'gt8' '4~8' nan]

* Driving Contextual Attributes (Number and Category of unique Values):
1.	destination ( 3 )  ['No Urgent Place' 'Home' 'Work']
2.	passanger ( 4 )  ['Alone' 'Friend(s)' 'Kid(s)' 'Partner']
3.	weather ( 3 )  ['Sunny' 'Rainy' 'Snowy']
4.	temperature ( 3 )  [55 80 30]
5.	time ( 5 )  ['2PM' '10AM' '6PM' '7AM' '10PM']
6.	toCoupon_GEQ5min ( 1 )  [1]
7.	toCoupon_GEQ15min ( 2 )  [0 1]
8.	toCoupon_GEQ25min ( 2 )  [0 1]
9.	direction_same ( 2 )  [0 1]
10.	direction_opp ( 2 )  [1 0]

* Coupon Attributes (Number and Category of unique Values):
1.	coupon ( 5 )  ['Restaurant(<20)' 'Coffee House' 'Carry out & Take away' 'Bar'  'Restaurant(20-50)']
2.	expiration ( 2 )  ['1d' '2h']

* Target Attribute:
1.	Y ( 2 )  [1 0]

Based on these characteristics of the dataset, some high level summary of the dataset includes:
The most common destination of the driver was 
'No Urgent Place', driving 'Alone' under 'Sunny' weather with temperature near 80 around 6 PM 
going to 'Coffee House' of '21' years of age and 'Married Partner' status, with education as 'Some college - no degree', 'Unemployed', earning in the range of '$25000 - $37499', 
either 'never' going to Bar, going to CoffeeHouse 'less1', taking CarryAway 1~3 times, going 1~3 times RestaurantLessThan20', Less1 to Restaurant20To50m, 
always accepting coupon GEQ 5 min driving distance and mostly rejecting when driving distance is GEQ 15 or 25 min away 
and has higher acceptance rate when the driving direction is opposite compared to same.

Other results of analysis are included in the Jupiter notebook.
