# Temperature-sensor-with-Firebase
 In this project it is described to get and push temperature data from dht11 using nodemcu to firebase.
## Components Used
    DHT11
    NodeMCU (ESP8266)
    Jumpers
 ## Circuit connection
    connect VCC -5V
    data-D4
    gnd -gnd
    
 ![alt-text](https://github.com/vinodhini-radhakrishnan/Temperature-sensor-with-Firebase/blob/master/connection.png)
  ## Firebase setup
  
   1.Open your browser and go to “firebase.google.com”

   2.At the right top corner go to “Go to Console”
    ![alt-text](https://github.com/vinodhini-radhakrishnan/Temperature-sensor-with-Firebase/blob/master/firebase%20setup1.png)
   3. Click on “Add project” and enter your project name
    ![alt-text](https://github.com/vinodhini-radhakrishnan/Temperature-sensor-with-Firebase/blob/master/firebase%20setup%202.png)
    ![alt-text](https://github.com/vinodhini-radhakrishnan/Temperature-sensor-with-Firebase/blob/master/firebase3.png)
   4.Now go to Settings Icon(Gear Icon) and click on “Project Settings”
    ![alt-text](https://github.com/vinodhini-radhakrishnan/Temperature-sensor-with-Firebase/blob/master/firebase4.png)
   5. Now click on “Service Accounts”.You can see two options “Firebase admin SDK” and “Database Secrets”
     ![alt-text](https://github.com/vinodhini-radhakrishnan/Temperature-sensor-with-Firebase/blob/master/firebase5.png)

   6.Click on “Database Secrets”

   7.Scroll on your project name and ”Show” option appears at right side of your project

   8.Click on “Show” and now you can see secret key created for your project.
    ![alt-text](https://github.com/vinodhini-radhakrishnan/Temperature-sensor-with-Firebase/blob/master/firebase6.png)
   9.Copy the secret key and save it to notepad. This is your “FIREBASE_AUTH” string which we have written in Arduino program above.
   10.Now go to “Database” on left control bar and click on it

   11. Scroll down and click on “Create Database”.
   12.Choose “Start in test mode” and click on “Enable”.
    ![alt-text](https://github.com/vinodhini-radhakrishnan/Temperature-sensor-with-Firebase/blob/master/firebase7.png)
   13.Now your database is created and you will have to come to this section again to control LED

   14. Now just above the database you  can see

   “https://your_project_name.firebaseio.com/”
   15.Just copy “your_project_name.firebaseio.com” without any slash and https and save it again to notepad just you had saved for secret key

   16. This is your “FIREBASE_HOST” string which we have written in Arduino program above.Add fields "temperature" and "humidity" in your project(firebase).
   17.Now put “FIREBASE_HOST” and “FIREBASE_AUTH” in Arduino program and upload the sketch. And we are done with setting up both sections. Now you can see the values updating in your firebase.
   
   
   ![alt-text](https://github.com/vinodhini-radhakrishnan/Temperature-sensor-with-Firebase/blob/master/firebase%20data.jpeg)
    
  For fabricating the circuit with a PCB , visit 
  For the tutorials on making case for the sensor , visit
  For the same project with thingspeak , visit
   ;with adafruit , visit ;with cyanne , visit .










 

 

 
   
