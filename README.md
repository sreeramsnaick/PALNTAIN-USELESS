# PALNTAIN-USELESS

Team Name: SPLASH

Team Lead: MANU KRISHNA KJ - COLLEGE OF ENGINEERING CHENGANNUR
Member 2: SREERAM S NAICK - OLLEGE OF ENGINEERING CHENGANNUR

*Project Description*
"Cut the Banana tree When There's Fire" "പുരക്കത്തുമ്പോ വാഴ വെട്ടുക"is a fun and useless automation project where an IR sensor detects fire and triggers a relay. The relay powers an RC transmitter, which activates a receiver connected to a servo motor with a blade — slicing the plantain in dramatic fashion!

*The Problem* 
What's the problem? Or is there even one?
In a world full of serious automation, we set out to solve a totally useless problem — how to instantly cut down a plantain the moment fire appears. Using sensors, relays, RC systems, and a dramatic servo-blade combo, we proudly over-engineered the silliest solution to a problem that never existed!

The Solution
We saw fire... and thought: “Quick! Someone slice a banana plan!” 🍌🔥
So we wired up an IR sensor to detect the drama, a relay to say “Go!”, and a servo motor with a blade ready to end the plantain’s life — all powered by an Arduino and controlled through an RC system.
It’s smart. It’s useless. It’s banana justice, served hot. 

*Technical Details*
For Hardware:
Arduino Uno – The brain of the operation
IR Sensor Module – Detects fire/light
Relay Module – Switches power to the transmitter
RC Transmitter & Receiver – Wireless signal communication
Servo Motor (with Blade) – The banana executioner 
Plantain (Vazha) – Our unfortunate hero



Schematic & Circuit
Circuit
https://drive.google.com/file/d/1-GgwcCEi0Ddm-6ibyTjiMh-ouewmphZQ/view?usp=drive_link








![Schematic]

https://drive.google.com/file/d/1o3t-0oMA5K9JGv_z55lnzq8ZbIjNJEqH/view?usp=drive_link

This system uses an Arduino UNO R4 to control a relay based on inputs from both an IR flame detection module and a wireless RC transmitter/receiver pair. It's useful for safety systems like fire-triggered automation with optional manual override via remote.

🧩 Components & Roles:
🔥 IR Sensor Module

Detects flame or high-intensity infrared light.

Sends a digital HIGH/LOW signal to Arduino (OUT pin).

Connected to Arduino digital pin D2.

📡 RF Receiver Module (e.g., 433 MHz)

Receives control signals wirelessly from an RC transmitter.

Data pin connected to digital pin D3 of Arduino.

Allows manual triggering of the relay remotely.

⚡ Relay Module

Acts as a switch to control high-voltage devices like motors, lights, etc.

IN pin connected to Arduino pin D8.

Turns ON when either a flame is detected or RC command is received.

🔲 Arduino UNO R4

Central microcontroller that reads both the IR sensor and RF receiver.

Decides whether to activate the relay.

🎮 RC Transmitter

Handheld remote that sends digital signals to trigger the receiver.





*Build Photos*
!Components

https://drive.google.com/file/d/1Zmh6wwZCX9mh1m_k31cWtVkbSvlugrMO/view?usp=drive_link

Arduino Uno ,IR Sensor Module ,Relay Module ,RC Transmitter & Receiver,Servo Motor (with Blade)


*Build*

https://drive.google.com/file/d/11wDaFCnmyXZaPT0TLb3AYNBzjLFYob7p/view?usp=drive_link

Connect IR sensor VCC, GND, and OUT to Arduino 5V, GND, and D2.
Connect RC receiver VCC, GND, and DATA to Arduino 5V, GND, and D3.
Connect relay module VCC, GND, and IN to Arduino 5V, GND, and D8.
Connect a load (like a bulb or fan) to relay’s NO and COM terminals.
Upload Arduino code to control relay based on IR sensor or RC signal.
Power the system and test with a flame or remote button.

![Final]

photo of final product

https://drive.google.com/file/d/1KOaLS6n2XMA6QdaDigrgq-NVb5d5TJRS/view?usp=drive_link
In the final build, we combined sensors, wireless modules, and a servo to create the most dramatic banana-cutting machine ever. Here's how it works:

Fire is detected by the IR sensor placed near the source.

The relay module gets activated, allowing current to flow to the RC transmitter.

The transmitter sends a wireless signal to the RC receiver.

The Arduino Uno on the receiver side picks up the signal and commands the servo motor.

The servo, equipped with a blade, rotates swiftly and slices the plantain (vazha) — mission complete!
Project Demo

Video

https://drive.google.com/file/d/1WQVwd5IIKVZq4UXVjsvJMUCdlrFPwgLr/view?usp=drive_link

The video showcases the dramatic journey from fire detection to banana destruction:

IR sensor detects fire or a light source — triggering the system.

Relay module activates, sending power to the RC transmitter.

The wireless RC setup communicates with the receiver.

The Arduino processes the signal and commands the servo motor.

The servo rotates with a blade 

Additional Demos
https://drive.google.com/file/d/1GBl_JqUSEyIBy2OFNHJgpvfbOxzcCgE7/view?usp=drive_link



Team Contributions
MANU KRISHNA AJ: HARDWARE SUPPORT
SREERAM S NAICK: SOFTWARE SUPPORT

