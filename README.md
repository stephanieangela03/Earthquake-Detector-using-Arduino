Earthquake Detector using Arduino


COMPONENTS
Arduino Uno: Microcontroller that serves as the core of the entire project.
ADXL335 Accelerometer: Sensor to detect vibrations caused by earthquakes.
Buzzer: To produce an alarm when an earthquake is detected.
220 Ohm Resistor: Used to regulate current to the buzzer or LED.
LED: Provides a visual indication when an earthquake is detected.
Breadboard: Connects all components without the need for soldering.
Jumper Wires: Small cables to connect components on the breadboard.


Cables and Connectors
Male to Male Jumper Cables: To connect pins on the Arduino to the breadboard.
USB Cable for Arduino: To connect the Arduino to a computer for programming and power supply.


BACKGROUND
Earthquakes are natural phenomena that can cause significant damage and endanger lives, especially in countries like Indonesia, located in the Pacific Ring of Fire. Early detection of earthquakes is crucial to mitigate the impact of these disasters.
Traditional earthquake detection systems use expensive and complex seismographs, making them inaccessible to the general public, especially in remote areas. However, advancements in microelectronics and the Internet of Things (IoT) now enable the creation of simpler, cheaper, and user-friendly earthquake detection systems.


PROBLEMS
1. Limited Access to Traditional Systems

2. High Costs

3. Operational Complexity

4. Limited Early Warning
  
6. Scarce Availability in Vulnerable Areas
   
7. Need for Flexible Solutions
   
8. Lack of Awareness and Education


SOLUTION: Earthquake Detection System with Arduino
Arduino is an open-source platform that is affordable and easy to program, ideal for creating an accessible and cost-effective earthquake detection system. Using sensors like accelerometers, this system can detect earthquake vibrations in real-time and provide early warnings. The Arduino-based system offers flexible solutions that can be tailored to the needs of users, making it suitable for various environments and communities.


OBJECTIVES
1. Improve Accessibility of Earthquake Detection
2. Reduce Costs
3. Simplify Usage
4. Provide Effective Early Warnings
5. Raise Awareness and Preparedness
6. Utilize the Latest IoT Technology
7. Encourage Innovation and Learning
8. DESIGN METHODS
9. Preparation of Components & Tools


Hardware Assembly
Microcontroller: Place the Arduino Uno on the breadboard.
Vibration Sensor: Connect the ADXL335 to the Arduino using jumper cables. Pin VCC to 3.3V, GND to GND, and data pins (X, Y, Z) to Arduino analog pins (A0, A1, A2).

Alarm and Indicator:
Connect the buzzer to a digital pin on the Arduino through a 220 Ohm resistor to regulate current.
Connect the LED to a digital pin on the Arduino through a 220 Ohm resistor.

Connections:
Use male to male jumper cables to connect all components.
Connect the Arduino to the computer using a USB cable.

Arduino Programming
IDE Setup:
Install the Arduino IDE on the computer.
Install the library for ADXL335.

Writing Code:
Write code to read data from the ADXL335.
Write code to trigger the alarm through the buzzer and LED if vibrations exceed a threshold.

Uploading Program:
Connect the Arduino to the computer using a USB cable.
Upload the program code to the Arduino.

Testing 
[Link to video]


WORK FLOW
Initialization:
Initialize components (sensor, display, buzzer, LED).

Data Reading:
Read acceleration data (X, Y, Z) from the ADXL335.

Data Processing:
Calculate vibration magnitude.
Compare the magnitude with the threshold.

Data Display:
Display a seismograph graph.

Early Warning:
If the magnitude exceeds the threshold, activate the buzzer and LED.
Continuous Monitoring:
Continue reading and processing data.


CONCLUSION

The Arduino-based earthquake detection system is an affordable, user-friendly, and effective solution for early earthquake warnings. With inexpensive components like the ADXL335 sensor, buzzer, and LED, the system can detect vibrations in real-time and provide quick notifications. Its flexibility and ease of customization make it suitable for various audiences, enhancing community preparedness and awareness of earthquake hazards.


SUGGESTIONS

Community Development: Form Arduino user communities to share knowledge.
Feature Development: Add wireless communication and integration with disaster monitoring systems.
Accuracy Improvement: Conduct further research to improve detection accuracy.
Outreach and Education: Conduct outreach campaigns and provide easily accessible tutorials.
Design Enhancement: Design smaller and lighter hardware versions.
Testing and Validation: Conduct further testing in various environmental conditions.
