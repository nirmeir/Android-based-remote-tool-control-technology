### Brief Explanation for Public Audience:

*Project Overview:*

We will be transforming a standard RC car into a smart vehicle that can be controlled remotely using an Android app called ANDRUAV. This project involves integrating a flight controller, typically used in drones, with the RC car to enable precise and responsive remote control.

*Key Components:*

1. *RC Car:* 
   - We'll start with a basic RC car (e.g., WLtoys A959).
   
2. *Flight Controller:* 
   - A small computer that manages the vehicle’s movements (e.g., Pixhawk Mini or Matek Systems F405-CTR).

3. *Sensors:*
   - An IMU (Inertial Measurement Unit) for detecting orientation (e.g., GY-521 MPU-6050).

4. *Communication Module:*
   - A Wi-Fi module (e.g., ESP8266) to enable communication between the car and the Android device.

5. *Android Device:*
   - A smartphone or tablet to run the ANDRUAV app.

*Steps to Achieve Remote Control:*

1. *Assemble the Hardware:*
   - Install the flight controller in the RC car.
   - Connect the steering and throttle controls to the flight controller.
   - Add the IMU sensor for orientation data.
   - Connect the Wi-Fi module for communication.

2. *Configure the Flight Controller:*
   - Use software like Mission Planner or QGroundControl to set up and calibrate the flight controller.
   - Configure the flight controller to control the car's steering and throttle.

3. *Set Up the ANDRUAV App:*
   - Install the ANDRUAV app on an Android device.
   - Connect the app to the flight controller via the Wi-Fi module.

4. *Test the Setup:*
   - Use the ANDRUAV app to send commands to the RC car (move forward, backward, turn left, right).
   - Ensure the car responds correctly and check the telemetry data.

*Outcome:*
- By the end of this project, we will have an RC car that can be controlled remotely using a smartphone, demonstrating the integration of modern technology with traditional RC vehicles. This project can be a stepping stone to more advanced applications, such as autonomous driving.

*Example Components:*
- RC Car (e.g., WLtoys A959)
- Flight Controller (e.g., Pixhawk Mini, Matek Systems F405-CTR)
- IMU Sensor (e.g., GY-521 MPU-6050)
- Wi-Fi Module (e.g., ESP8266)
- Android Device running the ANDRUAV app

This project combines practical engineering with modern tech, providing a hands-on experience in robotics and remote control systems.

###Previus projects:
In this course we got untill now 2 project:
1) The first project was about GNSS raw mesurments, we asked to find a location that recieved from few satellites by analize data set that we get.
2) The second project was about drone simulator and the main goal for the project was to try find good solution of small drone, flying inside indoor building without getting hit and crash. The project fully autonomous 2d drone simulator
