# 3d-classroom-simulator

## Introduction

The 3D Classroom Simulator is a virtual reality application that simulates a real-world classroom environment. It is intended for educators and students to experience a classroom setting remotely, making it easier to conduct virtual classes, training sessions, and interactive learning experiences.

## Features

- Realistic 3D classroom environment
- Interactive objects (e.g., desks, chairs, whiteboards)
- Avatar customization
- Multi-user support for virtual classes
- Voice and text communication
- Educational tools (e.g., presentation screens, projectors)

## Requirements

- Unity 3D (version 2019.4 or later)
- VR headset (optional but recommended)
- Microphone and speakers (for voice communication)

## Setup

1. **Clone the repository:**
   ```shell
   git clone https://github.com/yourusername/3d-classroom-simulator.git
   cd 3d-classroom-simulator

   open in vscode 
#  commands to run
step 1: run this in vscode terminal : 

g++ -o classroom classroom.cpp src/chair.cpp src/table.cpp src/cupboard.cpp src/window.cpp src/snowman.cpp src/fan.cpp src/shelf.cpp -I"C:\Libraries\freeglut\include" -I"C:\Libraries\glew\include" -L"C:\Libraries\freeglut\lib" -L"C:\Libraries\glew\lib" -lfreeglut -lglew32 -lopengl32 -lglu32

step2: after compling above commonds you will get next terminal root wait for some seconds to get it and runt this code. 

./classroom.exe
