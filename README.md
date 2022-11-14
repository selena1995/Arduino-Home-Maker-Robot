# Arduino-Home-Maker-Robot
I have made an Arduino Robot for house hold activities. This one can deliver any items like food, medicines, water, cell phone. clothes and many more things for one place to another.
## Story
Here in this instructable, I have made an Arduino Robot for house hold activities. This one can deliver any items like food, medicines, water, cell phone. clothes and many more things for one place to another. This is useful for those who work alone and have to manage the whole things in a short period of time. To make it simple, I have made it small in size and light in weight. But this could be modified according to your need. A big size and heavy weight robot could carry heavy things which will be more useful. Besides this article, I have also made a video on this robot which will help you for better understanding.
![image](https://user-images.githubusercontent.com/79990158/201729614-d131743f-f5dd-4db7-9c3a-db4dd588a34b.png)
## Why Automatic/Robot Home Maker Is Needed
There have so many robots are already available in the market who can clean the home, provides security protections, entertains people and many more. In case of my one, it is specialized in working side by side a person like other person works. Like, if you are cooking but on the same time you have to send a cup of tea to someone else, then the robot will carry the cup of tea to the other person. This will reduce work stress by working with a person. This will also use in hotels and restaurants in replacements of waiters.

[YouTube](https://youtu.be/Ox3EG2p2tDU)

## PARTS OF THE PROJECT
To make and understand it easily we have splatted this project into two main parts.

MECHANICAL Part
ELECTRONICS Part
for better explanation we have divided our ELECTRONICS Part into

Circuit and PCB
Assemble the electronics components
ARDUINO coding
## MECHANICAL PART
![image](https://user-images.githubusercontent.com/79990158/201730485-429a70ce-f735-4f2f-962b-b7685a9c3133.png)
![image](https://user-images.githubusercontent.com/79990158/201730509-419b4b32-8736-4daf-a147-57cf154c84d5.png)
![image](https://user-images.githubusercontent.com/79990158/201730542-e70f43d7-f378-4375-b2d7-2e1996f05030.png)
![image](https://user-images.githubusercontent.com/79990158/201730575-9f757339-4b28-4d6c-b2e6-cd1c3ea31f2a.png)
![image](https://user-images.githubusercontent.com/79990158/201730606-680146bd-cf19-4cc3-aeb7-bf4f5c03521f.png)

Here in this part we will need some PVC sheet to make the chassis, 4 TT gear motors with wheels, 1 submersible pump, one cooldrinks can which is completely optional. you may use anything else to make the water tank. This is considered as the easiest part of this robot. All you need to only cut the PVC sheet and assemble all the components together in a proper way. Here I have attached some pictures on this.

Here I have used 60rpm TTgear motors but you may vary the rpm according to your need. But one tips I want to share that, lower rpm motos are easy to control & they could be shown easily in any resentation. Thats it for this part. now we will move to our next part which is ELECTRONICS PART. Here we will directly enter into the circuit and pcb making part. This could be littlebit tough if you are a fresher in making electronics project but I will explain is as much easier as possible.

## CIRCUIT Diagram & PCB MAKING
Here I have attached the circuit or the connection diagram which is very easy to understand and make. Please follow this diagram when you are going to make this project.

![image](https://user-images.githubusercontent.com/79990158/201730894-616e0016-6f1b-493a-9a04-2b6f2266ca0a.png)
![image](https://user-images.githubusercontent.com/79990158/201730939-a9ac2117-1ae7-48c8-a875-00e0d9b06fe5.png)
![image](https://user-images.githubusercontent.com/79990158/201730999-056d1ca1-c65b-46a8-892d-2fae215ffbe8.png)
![image](https://user-images.githubusercontent.com/79990158/201731051-1402c4e4-5c3c-468e-9bdd-56defa7b2430.png)

This project will work or perform same with or without making pcb but I have made PCb boards for this project. Actually not only for this, I always do prefer making any project using Customized PCB boards. There have obviously some advantages of making any project using PCB boards. like

- Compact Size and Saving of Wire.
- Ease of Repair and Diagnostic. If in case of any damage, it's very easy to check and replace the particular failure components.
- Saving of Time.
- Immune to Movement.
- Tight connections and Short Circuits Avoided.
- Low Electronic Noise.
- Low Cost.
- Reliability.

So I always make PCB BOARD for my every project. As I have already mentioned before I have already attached a circuit diagram with this article so please download that before you are going to connect all of them together. In my case, I have made a customized PCB board from [JLCPCB](https://jlcpcb.com/IYB) to skip a few steps of wiring and make an easy connection between all the components.$2 for 5pcs PCBs, PCBA from $0, Register to Get Free Coupons here: https://jlcpcb.com/IYB. I really liked the PCB Boards as they are very high in quality.

## ASSEMBLE THE ELECTRONIC COMPONENTS
Now we will make all the components together. But before that please make sure that you have gathered all of them correctly. Here I have enlisted the components and also provided their pictures for your references. Hope this will help you to make this easier.
![image](https://user-images.githubusercontent.com/79990158/201732096-1b744898-60f2-4eca-95ac-39bbb6f321c1.png)
![image](https://user-images.githubusercontent.com/79990158/201732135-d30c1f8f-e9c0-46c8-abda-0e4d838dfb0c.png)
![image](https://user-images.githubusercontent.com/79990158/201732172-d5ccf089-9908-4840-82f8-7d42ca59ad4a.png)
![image](https://user-images.githubusercontent.com/79990158/201732226-1d2d9cf6-418a-41af-b15b-ab8bb4c0e535.png)


## SO THE COMPONENTS THOSE WILL BE NEEDED ARE
- ARDUINO NANO WITH CABLE
- L298N MOTOR DRIVER
- HC-05 BLUETOOTH MODULE
- M4 DIODE
- RED LED
- 78M05 VOLTAGE REGULATOR
- 220uF CAPACITOR
- TERMINAL BLOCKS
- HEADER PINS

Now please assemble all the components together to complete the project. this is very easy to do if you follow the simple connection diagram. But if you have any doubt on this you may watch this video for better understand

after assemble all the electronics part together only one thing will be left for us which is ARDUINO CODING. Trust me this part is really very easy as compared to these previous parts. So lets finish it...

![image](https://user-images.githubusercontent.com/79990158/201732851-cf905af6-2183-486c-a930-5732fbb10133.png)

## ARDUINO CODING

First of all you need to download Arduino IDE in your system which is a completely free software for all the users. You can easily download it from their official website. Then download the necessary libraries like- Adafruit Motor Shield library, Dabble, etc. and then you have to select the correct boards and ports. Here in this case we are using Arduino Nano so you have select Arduino Nano & for port you have to select the port that shows in the software after connection your Arduino Board with your system. It will be some thing like com port 3, com port 7, com port 4 etc. and so on.

![image](https://user-images.githubusercontent.com/79990158/201732992-97e0095c-44dc-458b-8d97-17146cb560aa.png)
![image](https://user-images.githubusercontent.com/79990158/201733019-ed3c9e87-526a-436d-b43c-c56aa72e9ca9.png)
![image](https://user-images.githubusercontent.com/79990158/201733055-17a7a97e-fbb4-4d95-8988-4569d445507c.png)

Then you need to download or copy the given Arduino code and pest it or open it and upload it in Arduino Nano.

PLEASE don't forget to disconnect the hc-05 Bluetooth module while uploading the code.

## CONNECTING VIA BLUETOOTH

![image](https://user-images.githubusercontent.com/79990158/201733185-69e27f56-f942-4e3b-8ec8-e710448be517.png)
![image](https://user-images.githubusercontent.com/79990158/201733211-1c0b8772-2426-4e93-80db-5dc3945e43d4.png)

After everything, finally we have to connect the robot with our android phone via Bluetooth. There have so many Android app easily available in play store. I have downloaded one of them and installed it in my Android phone. Then I have turned on the robot and searched for HC-05 Bluetooth. then they will as for the passwords. Most of the cases it is '1234'. then it will connect successfully with the robot. then open the app and run your bot.
