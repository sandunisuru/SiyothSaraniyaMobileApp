# Siyoth Saraniya 2017 Mobile App

This application was developed for Identifying Groups for the __Siyoth Saraniya 2017__ IT Faculty Freshers Night. 
It is an __Android__ Application written in Java. Used the __Zxing__ QR Code Scanning Library to aquire QR Codes to Identify Groups. 
All the group Deviding are based only this simple If condition :D. 

````java
        if(number%124==0){
            textViewName.setText("Black Pearl");
        }else if(number%233 == 0){
            textViewName.setText("Flying Dutchmen");
        }else if(number%342 == 0){
            textViewName.setText("Intercepter");
        }else if (number%413 == 0){
            textViewName.setText("Venganza");
        }else{
            textViewName.setText("There is no Group");
        }
 ````
 You can use this QR Library by adding this code to the app level gradle.
 ````java
        compile 'com.journeyapps:zxing-android-embedded:3.4.0'
 ````
 It is awsome and easy to use.
 
 Thank You.
        
        
