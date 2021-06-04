# Smart Agriculture System using IoT 
This project is about IoT-based smart agriculture, a system which is built for monitoring the crop field remotely.
In this proposed agricultural system IOT is implemented , in this system all the
information that are received via sensors and various parameters are given to the arduino
micro-controller as an analog input . A preset value of the soil moisture , temperature ,
humidity , PIR sensors are fixed in microcontroller and also for fencing . When it goes
beyond the particular threshold value , water is automatically irrigated to the crops and
once the required amount of water is fulfilled it will stop( automatically / manually ) . The
microcontroller transmit that information on the internet through a network of IOT in the
form of WiFi module ESP8266 attached to it . This enhances automated irrigation as water
pump can be switched on/off through information given to the controller . This approach is
for advanced agricultural process by automatic method without manpower by measuring
various parameters related to the field and thus improves agriculture.

# Features of the android and web facility:
This whole smart system can be automated by the microcontrollers , but the farmers can take several decisions manually depending on the situations . A web facility will provide the all information to the farmers to understand the present condition of the atmosphere and soil of their field even if they stay far away from the crop-field. For convenience purpose an android app is there to provide the same information briefly for the smartphone users. 
With the help of Google weather-API the website will predict weather condition for
the next few days , that will help the farmers to defend the upcoming situations.
In some cases the automated system decision might not matched with farmer's
wish . So a manual pump-driving option will be provided to the dashboard , which
will be manually controlled by farmers in some situations .
For the convenience of the farmers the website will be Google translated and
android app can be run in different local languages.



# Note: 
Due to some private reasons the code & API for webapp and android app cannot be shared. Also there are some arduino code for few sensors are missing in this repo. Still you can go through the project report to understand the essence of this project.
