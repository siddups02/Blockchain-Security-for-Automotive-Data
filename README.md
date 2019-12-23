# Blockchain-Security-for-Automotive-Data
This project provides security for Automotive data, data is acquired from OpenXC Device is written into Block-chain using Ethereum. We did Data Analysis on the data we get from OpenXC Device

- I used the OpenXC device to collect data from cars. Cars have OBD-II port to which the OpenXC device is plugged in and data is             transferred to the phone using Bluetooth.

- We get JSON format data on the phone, data is then transferred to the phone, I perform parsing of JSON data using the python JSON         library and take only required parameters to derive ratings.

- I have considered several parameters to provide Maintenance Rating on a car. The maintenance rating tells us how well an owner of the     car has maintained the car. Let it be regular service, engine efficiency, and brake conditions, etc. As the owner misses or fails to       maintain the car well the ratings go down for each parameter not meet.

- I came up with an interesting concept of Driving Behaviour Rating. I have calculated the four driving behavior ratings: SpeedingRating
  calculated from vehicle speed data, AcceleratingRating from acceleratorPedalPercentage, BrakeRating from vehicle acceleration,             drivingTimeRating from drivingTimeHour.
  
- The most important application of this project is for DMV's. Once the data analysis is performed and we have enough data sets to train a   machine learning model, DMV can approve a Driving License based on the ratings provided by the Data Analysis model for a certain period   of time rather than deciding on few minutes of driving. We can avoid Odometer rollback using blockchain on any automotive data. 

- Car Maintenance plays a very important role while selling and buying a used car. Several Car and engine Parameters are considered to       derive this rating. Engine Oil Temperature, Engine Coolant Temperature, Engine Manifold Pressure, Car Service Dates, etc are considered   in this rating.
