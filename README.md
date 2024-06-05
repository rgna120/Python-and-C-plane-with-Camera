
  # RC Spy Plane

This repository contains the code and instructions for building and controlling a DIY RC spy plane equipped with a camera. The project leverages a Raspberry Pi for video streaming and servo control, combining the ease of development in Python with the performance of C++.

### Features
* Real-Time Video Streaming: Stream live video from the Raspberry Pi camera module to any device on the same network.
* Servo Control: Control the servo motor angles through a web interface.
* Efficient and Responsive: Combines Python for high-level logic and C++ for performance-critical tasks.

### Components 
* Raspberry Pi
* Camera Module (e.g., Raspberry Pi Camera Module V2)
* Servo Motor
* WiringPi Library
* Flask (Python library)

## Getting Started
### Prerequisites
* Raspberry Pi with Raspberry Pi OS installed
* Camera Module connected to the Raspberry Pi
* WiringPi library installed on the Raspberry Pi

### Installation
* Clone the repository:
*     git clone https://github.com/your-username/rc-spy-plane.git
      cd rc-spy-plane
* Install WiringPi:
*     sudo apt update
      sudo apt install wiringpi
* Compile the C++ code:
*     g++ -shared -o libservo_control.so -fPIC servo_control.cpp -lwiringPi


