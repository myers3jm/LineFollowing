# LineFollowing
The logical design for a line-following robot written using LabVIEW.

Jared Myers is the author of the file "StudentCode.vi." All other files were provided for the task by the University of Cincinnati. As such, only "StudentCode.vi" is distributed under the terms of the GNU GPLv3. All other files are provided ONLY to demonstrate the operation of "StudentCode.vi," and are password-protected. By using this software, all parties agree that the contributors and publishers of the software are in no way liable for any loss or damage sustained due to use or misuse of the software.

The simulation sees a rectangular robot navigate a circuitous path represented by a black line. There are a few different tracks that can be tested, but the one we were evaluated on is called "Final Track, version 2."

REQUIREMENTS:
- NI LabVIEW (Community Edition, Version 21.0 acceptable)
- 1.66MB of free space on your hard disk

INSTRUCTIONS:
- Run "Project2_Final_Track_Simulator.vi" with NI LabVIEW
- Enter the following parameters into the appropriate boxes:
  - Robot Length: 7in
  - Robot Width: 4in
  - Number of Color Sensors: 2
  - Sensor 1 X Location: 0in
  - Sensor 1 Y Location: 1in
  - Sensor 1 Height: 1in
  - Sensor 2 X Location: 0in
  - Sensor 2 Y Location: -1in
  - Sensor 2 Height: 1in

- The values for Sensor 1 Mode and Sensor 2 Mode can be set to any of the options available. Here are descriptions of what conditions each mode is intended for:
  - Ambient: The sensor measures the light level seen by the color sensor based on the ambient lighting in the environment in which the robot is operating.
  - Reflected: The sensor measures the light level seen by the color sensor based on a light source emitted by the color sensor.
  - Detect: The sensor measures the color of light observed by the color sensor as an integer, corresponding to the following values:
    - No color: 0
    - Black: 1
    - Blue: 2
    - Green: 3
    - Yellow: 4
    - Red: 5
    - White: 6
    - Brown: 7


