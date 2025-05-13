# Cybersecurity : CSN150-ESP32-CAM
## Camera Installation & Use

## Name of Project
ESP32-CAM use and setup

## Purpose


## Equipment
* [ESP32Cam](https://www.amazon.com/Aideepen-ESP32-CAM-Bluetooth-ESP32-CAM-MB-Arduino/dp/B08P2578LV/ref=sr_1_3?crid=4FY0ECFW0ZX7&keywords=ESP32+Cam&qid=1678902050&sprefix=esp32+cam%2Caps%2C240&sr=8-3)

* [USB Micro Data Cable](https://www.amazon.com/AmazonBasics-Male-Micro-Cable-Black/dp/B0711PVX6Z/ref=sr_1_1_sspa?keywords=micro+usb+data+cable&qid=1678902214&sprefix=Micro+USB+data+%2Caps%2C89&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUFaU0NaUVZHU1RFUlAmZW5jcnlwdGVkSWQ9QTA3NTA4MDVFVERCS01HVlgxM1YmZW5jcnlwdGVkQWRJZD1BMDE4NTE1NTIwWUdONkdWSzU1M1Amd2lkZ2V0TmFtZT1zcF9hdGYmYWN0aW9uPWNsaWNrUmVkaXJlY3QmZG9Ob3RMb2dDbGljaz10cnVl)

## Links to documentation

##### Video 1: 

##### Other Links: 


## Steps I followed

First, that was going to select board, then select other board and ports after that I click on search board and typed AI and select AI thinker ESP 32 cam, after that I select the port with a available USB connection in my case "COM5 Port (USB)"

Second, I went to file click on examples and select ESP 32 then camera and finally select camera web server

After all these steps, I get to the new interface with the show code

Then we're gonna uncommon the camera module AI thinker and disable or make it a comment the default camera model ESP

Next, we're gonna connect our code and ESP 32 to the Wi-Fi by replacing the asterisk by our Wi-Fi name and password.

And finally click the arrow to upload the code and on serial monitor menu change the BAUD to 115,200 
Then will be a be able to see that the Wi-Fi is connecting to the Internet and we're gonna get an HTTP address we can use to access or camera on the web

NOTE: the camera should be axis via device in the same network we programmed the ESP 32 cam




## Problems

During this lab, I encountered no significant challenges other than locating the serial monitor tap. In my case, it was situated on the top right corner of the program interface, where I could enable it. Subsequently, I discovered the BAUD tap, which allowed me to modify the baud rate and monitor the address and Wi-Fi connectivity status.

### Pictures
![image alt](https://github.com/stephanbluitt/CSN150---ESP32CAM/edit/main/README.md#:~:text=IMG_4200.HEIC)
![image alt](https://github.com/stephanbluitt/CSN150---ESP32CAM/edit/main/README.md#:~:text=IMG_4201.HEIC)
![image alt](https://github.com/stephanbluitt/CSN150---ESP32CAM/edit/main/README.md#:~:text=IMG_4202.HEIC)
![image alt](https://github.com/stephanbluitt/CSN150---ESP32CAM/edit/main/README.md#:~:text=IMG_4203.HEIC)
![image alt](https://github.com/stephanbluitt/CSN150---ESP32CAM/edit/main/README.md#:~:text=IMG_4204.HEIC)
![image alt](https://github.com/stephanbluitt/CSN150---ESP32CAM/edit/main/README.md#:~:text=IMG_4206.HEIC)
![image alt](https://github.com/stephanbluitt/CSN150---ESP32CAM/edit/main/README.md#:~:text=IMG_4207.HEIC)
![image alt](https://github.com/stephanbluitt/CSN150---ESP32CAM/edit/main/README.md#:~:text=IMG_4208.HEIC)



## Final Report

In the image description, I have provided instructions on how to install “ESP32-CAM.”
