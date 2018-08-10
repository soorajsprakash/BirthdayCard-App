# BirthdayCard-App

**Version 1.0.0** 

A simple Birthday card Android Application which you can modify in your own way using Android Studio and send it to your friends in their birthday.

## Pre-requisites
* Android SDK v24
* Android Build Tools v24.0.2
* Android Support Repository v24.2.0



## Getting Started

### 1.Using the option "open an existing Android Studio project" in Android Studio :
Clone the repository into your preferred directory in your PC, load the project into android studio and modify it in your own ways.

### 2. Using the option "Check out project from Version Control" in Android Studio :
Fork this repository first, and then select the mentioned option. Select git from the drop down menu. Authorize your github account using your credentials in it. And then select the repository in the screen shown.

![screenshot 13](https://user-images.githubusercontent.com/26853789/43415661-cfc620a4-9453-11e8-8a52-eb3ca0c38640.png)


## Modifications you want to make:

### 1. Change the Background picture
You can change the background picture by replacing the "androidparty.jpg" file from the directory: 

[ BirthdayCard-App>src>main>res>drawable ]

with your friends best or funny picture. 

![screenshot 16](https://user-images.githubusercontent.com/26853789/43415842-44974ff2-9454-11e8-8e5e-e2934711ae8c.png)

Also change the image name in  [ BirthdayCard-App>src>main>res>layout>activity_main.xml ] line number: 14 "@drawable/friends_pic_name".
Replace the name "androidparty" with the name of the image you need. You dont have to type in the file extention.

![screenshot 19](https://user-images.githubusercontent.com/26853789/43416134-17d466a2-9455-11e8-9386-537cca8f6788.png)

### 2. Change the text "Happy Bday my Friend" to your choice
You can change the text by replacing the text in "Quotes" from line 23 of the file (activity_main.xml) from the directory:  

[ BirthdayCard-App>src>main>res>layout>activity_main.xml ].

![screenshot 21](https://user-images.githubusercontent.com/26853789/43416243-60a1ea44-9455-11e8-8282-07fb5b3632f8.png)


### 3. Change the text "From Sooraj" to your choice
You can change the text by replacing the text in "Quotes" from line 36 of the file (activity_main.xml) from the directory:  

[ BirthdayCard-App>src>main>res>layout>activity_main.xml ].

![screenshot 23](https://user-images.githubusercontent.com/26853789/43416320-937f2a8a-9455-11e8-92f8-af69f9ebfca3.png)


## Building the App:
You can build the Application with Android Studio by clicking on the Run App option (green play button on the tooolbar) after making your modifications wherever necessary and running them on an emulator or Android device.
And then click on the Hammer icon on the toolbar to build the apk file.


## Output:
You can find the application in the following directory

[ BirthdayCard-App\app\build\outputs\apk\debug\ ]
