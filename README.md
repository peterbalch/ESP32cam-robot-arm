# ESP32cam-robot-arm
files for my ESP32cam robot arm Instructable

<link???>

The ESP32cam is a very nice processor and camera which should be useful in a wide range of robotics projects. But when you look on the web most ESP32cam projects are very similar: "here's an ESP32cam, let's connect it to a PC over Wi-Fi and use the PC to recognise a face or record video". 

The ESP32cam is acting as not much more than a wireless webcam. It is simply a peripheral to a PC. It should be capable of more than that. It ought to be very useful in robots that are not tethered to a PC through Wi-Fi.

I'm interested in assembly-robotics so I started to investigate how useful an ESP32cam would be. Can the robot use vision to put things together? 

This project is the first part of that robotics project. I was surprised at how hard it is to get the popular AI-Thinker ESP32cam to do anything standalone. The more I searched the web, the more people I found running up against the same problems - there just aren't enough pins exposed. One commentator suggested that we ahould think of the ESP32cam as a single purpose device - it's a Wi-Fi camera that can also save images to an SD card. 
