# Bank Surveillence and Security System using Arduino
 
The model uses 6 Arduinos which are used as 3 pairs (1 master and 1 slave arduino in each pair). It can be used as a vault security system. The working is explained below  :<br/>

## Premise
This model assumes that to reach the vault a person must unlock 2 doors. The first door opens to a passageway leading to the vault, which is secured by another lock. An authorized person will have the access codes to both the doors and hence can access the vault. 2 PIR sensors are placed near the entry and exit doors of the vault to display the number of people present inside the vault at anytime. For implementing fire safety we have used a smoke sensor which will detect the instensity of the smoke. An ultrasonic sensor is placed in the passageway to detect the presence of people in the passage. Servo motors are being used to represent vents for smoke to escape and the doors. The LCD displays, buzzer and LEDs are being used as an alert system.

## Working 
A person which requires access to the vault will have to enter the keycode to the passage door in the keypad lock. If he/she opens enters the correct code and opens the door the ultrasonic sensor will be activated. Then the person will have to enter the correct access code in the keypad of the vault door. There will be only 3 incorrect attempts allowed, if the person exceeds that limit, then both the passage door and the vault door will be locked and an alarm will be raised. An LCD Display displays the number of people inside the vault. The smoke sensor keeps sensing the smoke instensity whenever it goes above a threshold, an alarm for evacuation will be raised and the vents will open up for the smoke to escape. 

Circuit Diagram :










Working simulation :





You are welcome to try it out yourself in tinkercad using the link : https://www.tinkercad.com/things/3mYpz2mTJ1w-securitysystem/editel?sharecode=1wksg43dw1fd9AYJUV_BJQuiheP10oxFhdwtPbu4ACY
