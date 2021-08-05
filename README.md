# Drone-Transmitter-and-receiver


![alt text](https://github.com/akarsh98/DIY-Radio-Controller-for-Drone-Arduino-Based-Quadcopter/blob/main/Images/Drine%20Receiver.jpg)

In this project, we are going to make an Arduino-based Radio Control system for our Arduino-based drone. We will make two different circuits in this project. One is for the Transmission i.e the Remote Control and the other one is for the reception of the signals sent by the Transmitter and will be placed on the Drone. The Transmitter and Receiver both are Arduino-based. The module that we are going to use to establish a connection between the remote and the Drone is the NRF24L01 Transceiver module.


![alt text](https://github.com/akarsh98/DIY-Radio-Controller-for-Drone-Arduino-Based-Quadcopter/blob/main/Images/Drone%20Transmitter.jpg)

The nRF24L01 is a wireless transceiver module, meaning each module can both send as well as receive data. They operate at the frequency of 2.4GHz, which falls under the ISM band, and hence it is legal to use in almost all countries for engineering applications. The modules when operated efficiently can cover a distance of 100 meters (200 feet) which makes it a great choice for all wireless remote-controlled projects. The module operates at 3.3V hence can be easily used with 3.2V systems or 5V systems. Each module has an address range of 125 and each module can communicate with 6 other modules hence it is possible to have multiple wireless units communicating with each other in a particular area. Hence mesh networks or other types of networks are possible using this module..

![alt text](https://github.com/akarsh98/DIY-Radio-Controller-for-Drone-Arduino-Based-Quadcopter/blob/main/Images/test%20rx.JPG)

While making the Transmitter or the Remote Control, we will Connect the Arduino UNO with the NRF module and connect it with two Joystick modules for sending commands to our drone. On the other hand, the receiver will only have the Arduino UNO and the NRF module connected to each other. The Receiver that we will place on the drone will be connected to the Flight Controller of our drone to which the received commands will be passed and according to those commands the motors will be operated controlling the flight of our drone. 


![alt text](https://github.com/akarsh98/Controlling-ESP8266-with-Alexa/blob/master/images/pcbway.JPG?raw=true)

You must check out [PCBWAY](https://www.pcbway.com/) for ordering PCBs online for cheap!

You get 10 good-quality PCBs manufactured and shipped to your doorstep for cheap. You will also get a discount on shipping on your first order. Upload your Gerber files onto [PCBWAY](https://www.pcbway.com/) to get them manufactured with good quality and quick turnaround time. Check out their online [Gerber viewer](https://www.pcbway.com/project/OnlineGerberViewer.html) function. PCBWAY takes care of its customers a lot that's why they offer reward points with every purchase that you make from them these reward points can be redeemed for various useful items from their [gift shop](https://www.pcbway.com/project/gifts.html).
