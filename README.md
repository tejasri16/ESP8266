Integrated Smart Home Security and Energy Management System
This project integrates advanced security mechanisms and automated environmental management to enhance home safety and energy efficiency. The system is divided into two primary components:

1. Security System
Fingerprint Module (R305):
Adds and verifies fingerprints for secure access, limiting entry to authorized users.

Keypad (4x4):
Acts as a backup access method if the fingerprint system is unavailable.

Camera Recognition:
Activates after three failed access attempts, capturing an image of the individual and sending it to the authorized user for immediate notification.

Solenoid Lock:
Engages or disengages access control, providing secure physical entry management.

2. Automation System
Temperature & Humidity Sensor:
Monitors environmental conditions and transmits data to a Bluetooth-connected device, aiding energy-saving actions like optimizing cooling or heating.

Flame Sensor:
Detects potential fire hazards and sends early warnings to prevent accidents.

Switch and Relay:
Controls connected electrical devices based on sensor inputs, enabling efficient automation.

Equipment Used

Overall Circuit:
![WhatsApp Image 2024-11-18 at 02 59 23_9d414571](https://github.com/user-attachments/assets/8d890998-89ce-48f1-86f7-a35287b6522c)


The complete hardware setup showcasing the integration of all components in the system.

Arduino Mega:
![WhatsApp Image 2024-11-18 at 03 07 56_8c0e15a7](https://github.com/user-attachments/assets/3b2c835f-ed6d-4474-b31f-a352b12d3ac9)


The main controller responsible for managing the overall functionality.

ESP8266:
![WhatsApp Image 2024-11-18 at 03 08 12_ebdcd438](https://github.com/user-attachments/assets/a2e891e5-2efd-4cac-a131-ad046b9daa56)


Enables Wi-Fi communication for remote monitoring and control.

Fingerprint Module:
![WhatsApp Image 2024-11-18 at 03 08 38_503cadaf](https://github.com/user-attachments/assets/a95402d7-402e-43fa-a010-9673be428738)


Used to store and verify fingerprints for secure user authentication.

Keypad (4x4):
![WhatsApp Image 2024-11-18 at 03 09 02_2a9e936e](https://github.com/user-attachments/assets/98f1b8e7-2f6e-4885-b961-427f8765b998)


An alternative input method for access control when the fingerprint system fails.

FHD Webcam:
![WhatsApp Image 2024-11-18 at 03 09 26_429299c6](https://github.com/user-attachments/assets/069c3de3-6253-4688-8949-67c382be9ba6)


Captures images of unauthorized individuals after failed access attempts.

Raspberry Pi:
![WhatsApp Image 2024-11-18 at 03 09 46_472c2c97](https://github.com/user-attachments/assets/426e066d-1e82-4a31-97ec-0045ec60dbf2)


Handles image processing and notification delivery for security purposes.

Relay Module:
![WhatsApp Image 2024-11-18 at 03 10 04_d174cc5f](https://github.com/user-attachments/assets/ff7a0257-e9e2-4f8b-8067-af06a49ae4ab)


Facilitates automation by controlling electrical devices based on sensor inputs.

Solenoid Lock:
![WhatsApp Image 2024-11-18 at 03 10 24_7c299eee](https://github.com/user-attachments/assets/b597b8d0-adc6-4da9-bd21-55fa632bbb21)


Provides secure locking and unlocking mechanisms for physical access control.
