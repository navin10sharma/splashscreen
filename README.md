#(Please Follow the following Setup and run Ionic2 App)<br />

1.npm install -g ionic cordova <br />
2.ionic info (It will check you current CLI version)<br />

MY System Config<br />
--------------------------------
--------------------------------

Your system information:<br />

Cordova CLI: You have been opted out of telemetry. To change this, run: cordova telemetry on.
6.3.1<br />

Gulp version:  CLI version 1.2.2 <br />
Gulp local:  <br />
Ionic Framework Version: 2.0.0-rc.1 <br />
Ionic CLI Version: 2.1.4 <br />
Ionic App Lib Version: 2.1.2 <br />
Ionic App Scripts Version: 0.0.36 <br />
ios-deploy version: 1.8.6  <br />
ios-sim version: 5.0.8 <br />
OS: Mac OS X Sierra <br />
Node Version: v4.5.0 <br />
Xcode version: Xcode 8.0 Build version 8A218a  <br />

<h2>Please Follow the Follow Setps to Create Demo project : </h2><br />
1.ionic start projectName --v2   {This command will get demo project and install all the dependencies } <br />
2.cd projectName <br />
3.ionic serve {it will run your project in browser} <br />

<h2> To Run your app in simulator you need to follow below command </h1> <br/>
1.ionic platform add ios/android {You need to add platform for which you want to make build} <br />
2.ionic build ios/android { it will build your apps for required platform} <br />
3.ionic run android/ios {it will open your apps in simulator but first you need to install  <br />
   Xcode and Android simulator you can also use Genymotion simulator for android it will be fast compare to 
   Default android simulator}  <br />
   
4.ionic run ios --target='iPhone-6,10.0' { if your xcode install it will open your iphone 6 simulator } <br />

5.ionic run ios --device {if your device connected to machine it will open app in device as well } <br />


To Create a splash and icon you need to Follow same Command as ionic 1 <br /> 

ionic resources ios --splash <br /> 
ionic resources android --splash <br />

ionic resources ios --icon <br /> 
ionic resources android --icon <br />






