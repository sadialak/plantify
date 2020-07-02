# Plantify
Build an AR app that shows a plant in your room when you tap your phones display.

   # Getting Started
      Steps to create this application:

      1.       Create a new project and name it

      2.       Click File > Build Settings then select Android and Switch Platforms on the bottom right corner. This will change the platform your building for to Android.

      3.       Go to Edit > Project Settings > Player and in the XR Settings section select Vuforia Augmented Reality Supported

 

      Implementing Ground Plane:

      1.       Go to GameObject > Vuforia Engine > AR Camera. This will create an AR Camera. You can now delete the Main Camera in your Hierarchy.

      2.       Go to GameObject > Vuforia Engine > Ground Plane > Ground Plane Stage. 

      3.       Go to GameObject > 3D Object > Capsule. Make sure to drag the capsule into the Ground Plane Stage in your Hierarchy.

      4.       Go to GameObject > Vuforia Engine > Ground Plane > Plane Finder and drag the Ground Plane Stage from your Hierarchy into the Anchor Stage of your Plane Finder                      showing in the Inspector.

 

 

      Implementing a plant model into Ground Plane:

      I decide to use Sketchfab to download a model of a plant that was already made by someone else. Sketchfab is a platform where artists can upload their 3D Models and make           them available for Download for free or for money.

      1.       Sketchfab is available as a Plugg-In for Unity.

               This is a guide on how to install it. You also have to create an account.

               https://github.com/sketchfab/unity-plugin/releases/tag/1.1.1

      2.       Then go to Sketchfab in the Menu > Browse Sketchfab and log in

      3.       Now you can search for indoor plants in the search bar. Make sure that “Staff Picked” is not ticket otherwise it won’t show you all results of your search.

      4.       I selected “Indoor Plant” by hako and downloaded it

      5.       Click on Import in the Assets section and on Indoor_Plant. Now you can drag the Indoor Plant into your scene and it will appear. 

      6.       Make sure to frequently save your progress.




   # Prerequisites
       Unity 2018.4.23f1
       Vuforia Engine
       Android Studio
       JDK
    
   # Installing

        1.       Go to Edit > Preferences > External Tools and select an SDK and JDK. If you don’t already have it you need to download Android Studio for the SDK and select                      Android 8.0 and Java for the JDK

        2.       Go to Edit > Project Settings > Player and under Company and Product Name change it to Plantify. Then under Other Settings for Package Name change it to                          com.Plantify.Plantify

        3.       Go to File > Build Settings then click on Add Open Scene and then Build

        4.       Now if you have your Phone connected to your Notebook by USB you can just copy your .apk to the Download section of your phone.

        5.       Download ASTRO Filemanager, open it, go to the download folder and select the Planify app. It wil unpack and install it on your phone. Then you can open it. If                  you tap on the screen of your phone it should show something like in the picture below
        
   # Runing the tests
    
    
  
