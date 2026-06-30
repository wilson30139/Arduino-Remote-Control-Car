# Remote Control Car
## Introduction
This repository contains an Arduino-based remote control car developed using Arduino components and Bluetooth communication. It supports smartphone-based remote control and demonstrates the integration of embedded hardware with wireless communication topologies.

The project showcases embedded system development, Bluetooth communication, mobile device integration, and real-time vehicle control through Arduino programming.

## Feature
### Smartphone Control Mode
- Control the vehicle through a Bluetooth-connected smartphone.
- Support forward, backward, left, and right movement.
### Object Detection Mode
- Detect nearby objects using sensors.
- Control the vehicle based on object detection result.
### Mode Switching
- Switch between Smartphone Control Mode and Object Detection Mode using an RFID card.
### Vehicle Lighting System
- The left indicator flashes when turning left.
- The right indicator flashes when turning right.
- Both indicator flash when moving forward.
### Reverse Warning
- The vehicle emits a warning sound while reversing.

## Demo
### Smartphone Control Mode
- Video: https://drive.google.com/file/d/1Ixgjq7noOMGMLLOR5go2chjAUQ6HfZK0/view?usp=sharing

### Object Detection Mode
- Video: https://drive.google.com/file/d/1O02ncYHhMH47T7JDWd0g-15L1aCM132o/view?usp=sharing

### Mode Switching
- Video: https://drive.google.com/file/d/1xS2wzoL0zJpnxVsiR2OIY92YpohqmJAO/view?usp=sharing

## Screenshot
<p align="center">
  <img width="400" alt="Remote Control Car" src="https://github.com/user-attachments/assets/c3dd098b-f1ad-4041-b354-062449b4eda1" /><br>
  <strong>Figure 1: Remote Control Car</strong>
</p>

Figure 1 shows the completed Arduino-based remote control car. This repository contains the source code developed for the project, which was uploaded to the Arduino board to control the vehicle. The hardware components were assembled to build the final remote control car shown in the figure.


<p align="center">
  <img width="400" alt="Remote Control Car 2" src="https://github.com/user-attachments/assets/ce52b765-03f9-452a-8623-e8f1387d9db8" /><br>
  <strong>Figure 2: Smartphone Control Mode</strong>
</p>

Figure 2 demonstrates the Smartphone Control Mode. A smartphone connects to the remote control car via Bluetooth, allowing users to remotely control the vehicle's movement, including forward, backward, left, and right directions.

<p align="center">
  <img width="400" alt="Remote Control Car 3" src="https://github.com/user-attachments/assets/2569da49-81b2-4dad-af37-e3607bd55cea" /><br>
  <strong>Figure 3: Object Detection Mode</strong>
</p>

Figure 3 demonstrates the Object Detection Mode. In this mode, the vehicle automatically detects nearby objects using sensors and moves toward the detected object. In this demonstration, a hand is used as the target object.

<p align="center">
  <img width="400" alt="Remote Control Car 4" src="https://github.com/user-attachments/assets/b719cb94-6a67-44fc-b68d-aa7e8bf18b05" /><br>
  <strong>Figure 4: Mode Switching</strong>
</p>

Figure 4 shows the mode-switching mechanism of the remote control car. The blue module in the center is the RFID reader, which allows users to switch between **Smartphone Control Mode** and **Object Detection Mode** by scanning an RFID card.

The LCD display below the RFID reader indicates the vehicle's current operating mode. The Bluetooth module on the left is responsible for wireless communication with the smartphone. The LED indicators on both sides display the vehicle's movement direction, including left turn, right turn, and forward movement.

## Technologies

## Project Structure
