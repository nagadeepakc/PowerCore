# PowerCore
> Team Members:  Naga Deepak Chelluri (nc4sq) | Cameron Peters (cwp9fq) | Yugank Singhal (ys5ab) | Khalid AL­Hassan (kna5de)

## Background
The PowerCore is a modified power strip that utilizes various technologies to monitor the environment, gather user data, and control multiple electrical appliances. The PowerCore home automation system facilitates tasks that a resident frequently performs in his or her day to day life to obtain a more relaxed and efficient life environment, acting as a control hub for the home. The PowerCore uses data taken from a user-driven web application and various onboard sensors to regulate power to devices on the modified power strip. This system is being developed on the MyRio platform and is programmed using LabVIEW. 

## Technical Description
PowerCore is comprised of three primary components: the web application, the sensor package, and the modified power strip. The goal is to regulate power to a user's devices based on their desired environment, in hopes to maintain homeostasis. The sensor package will receive data from two sources, the onboard sensors and the web application. This gives the sensor package insight into both the current environment and the users’ environmental preferences. Using this information, the sensor package determines which devices should be turned on in any given time and then sends this information to the modified power strip, allowing it to turn on or off devices as needed. We chose to do the majority of the processing on the sensor package because it reduces the bandwidth needed to establish the required amount of communication between MyRios.

## Past Experience and Challenges 
Given the different components which comprise this project, we have had to utilize skills learned in previous courses, including but not limited to web and mobile development, digital logic design, electronics, advances software development, signals and systems, and embedded systems. However, these courses have not prepared us for everything. The challenges we have overcome so far are designing the protocol for communication between the three components, implementing network shared variables, and finding the perfect sensors for our sensor package. Currently, we are focusing our attention on designing the exact state machine for the sensor package. Once we have overcome this challenge, we will be able to have any sensor control any outlet on our power strip.

## Team members’ Responsibilities:
* Naga Deepak Chelluri - LabView Programming
* Cameron Peters  - Modified Power Strip Design
* Yugank Singhal - Web Site Programming
* Khalid AL­Hassan - Sensor Package Design

## Sensors
DHT11 (Temperature and Humidity sensor) Datasheet:
* http://www.dfrobot.com/image/data/DFR0067/DFR0067_DS_10_en.pdf
Ambient Light sensor Datasheet
* https://www.sparkfun.com/datasheets/Sensors/Imaging/TEMT6000.pdf
