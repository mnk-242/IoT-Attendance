# IoT-Attendance
IoT and RFID based Attendance System.

This repository consists of the Arduino code that was embedded into the microcontroller as well as the python script that was run on my workstation to recieve, store and transmit data to Google Drive. The overall project consists of a full report and research.

# Aim 
The aim for this project was to record attendance, store it on the workstation as well as transfer the data to the cloud (google sheet) for remote access.
The project was also supposed to record attendance with the name of the attendee, the tag ID, the date and time, which it successfully did. It can store over a 100+ logs of attendance to the cloud.

...
# Hardware Used
Arduino UNO (Microcontroller)
RFID Reader (MFRC522)
Jumper Wires
USB-B cable (for Arduino UNO)
RFID tags (4)
Breadboard 
LED (2)
....

# Software Used
Arduino IDE
Visual Studio Code
Excel Sheet
Google Cloud/Drive
Google Sheets
....


# Issues I ran into during this Project

**Soldering Issue:**
Cold solder joints caused enormous intigration issues with the RFID, it was also difficult to identify.
Based on the powers fluctuations and the error message, the soldering was an issue.
Resoldering them is the only fix to ensure proper communication.

**Faulty Components**
Certain componenets used within this project were undeniable faulty, the communication errors surprisingly made the issue difficult to identify.
By replacing and downsizing the project, and focusing on the functionality of certain components, it was easy to narrow down what component was causing such errors.

