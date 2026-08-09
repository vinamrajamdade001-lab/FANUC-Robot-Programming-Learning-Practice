# FANUC-Robot-Programming-Learning-Practice
Learning FANUC industrial robot programming through Teach Pendant practice, covering motion instructions, robot programs, tool and frame configuration, I/O interfaces, controller operations, and industrial automation concepts.


##  About This Repository

This repository contains my learning and practice work while exploring **FANUC industrial robot programming** using the **Teach Pendant**.

The main focus is understanding how a FANUC robot is programmed and operated in an industrial environment — from basic pendant navigation and robot movements to creating programs, using instructions, configuring tools, and understanding how different controller interfaces work.

This repository serves as a practical reference for my progress in **industrial robotics, automation, and mechatronics engineering**.



## Learning Objectives

Through this learning process, I am working toward understanding:

* FANUC Teach Pendant operation
* Robot controller interface and menus
* Creating and editing robot programs
* Robot motion instructions
* Position and joint control
* Tool and frame configuration
* Input/output instructions
* Program execution and monitoring
* Robot alarms and basic troubleshooting
* Program and file management
* Robot communication concepts
* External-axis concepts
* Basic robot kinematics



## 🖥️ FANUC Teach Pendant

The **Teach Pendant** is the primary interface used to interact with and program the FANUC robot.

I am learning how to use the pendant to:

* Navigate controller menus
* Select and edit programs
* Jog the robot
* Record robot positions
* Modify motion instructions
* Configure tools and frames
* Monitor inputs and outputs
* View robot status
* Handle alarms
* Execute and test programs

Understanding the Teach Pendant is an important foundation for working with FANUC industrial robots.



##  Robot Programming Instructions

A major part of my learning is understanding the different instructions available in FANUC programming.

### Motion Instructions

Learning how to control robot movement using different motion types and position data.

Examples include:

* `J` – Joint motion
* `L` – Linear motion
* `C` – Circular motion

These instructions determine how the robot moves between programmed positions.



### Position Instructions

Learning how robot positions are recorded, stored, and modified.

Important concepts include:

* Cartesian position
* Joint position
* Position registers
* Position modification
* Robot configuration



### I/O Instructions

Learning how the robot interacts with external equipment through digital inputs and outputs.

Examples include:

* Digital Output
* Digital Input
* Waiting for an input
* Activating an output
* Using I/O conditions in programs

These instructions are important for connecting robots with machines, sensors, PLCs, grippers, and other automation equipment.


### Program Control Instructions

Learning how to control the flow of a robot program.

Topics include:

* `IF`
* `JMP`
* `LBL`
* `CALL`
* `WAIT`
* Program loops
* Conditional execution

These instructions help create programs that respond to different conditions instead of following only a fixed sequence.


##  Robot Jogging

I am learning how to manually control the robot using the Teach Pendant.

Different jogging methods include:

* Joint jogging
* World coordinates
* Tool coordinates
* User coordinates

Understanding these coordinate systems helps in positioning the robot correctly and creating accurate motion programs.



##  Tool & Frame Configuration

An important part of robot programming is understanding coordinate systems.

### Tool Frame

The tool frame defines the position and orientation of the tool attached to the robot.

Important TCP parameters include:

* X
* Y
* Z
* W
* P
* R

Correct tool configuration is necessary for predictable robot movement.

### User Frame

User frames allow robot positions to be defined relative to a particular workpiece or workspace.

I am learning how tool and user frames affect robot movement and position data.



##  Position Registers

Position Registers provide a way to store and modify robot positions during program execution.

I am learning how position registers can be used for:

* Storing positions
* Modifying positions
* Creating flexible programs
* Changing robot targets during execution



##  I/O Interface

The FANUC controller provides interfaces for communicating with external devices.

I am learning how to understand:

* Digital inputs
* Digital outputs
* I/O status
* I/O assignments
* Sensor signals
* Actuator control

This is particularly important for **industrial automation**, where robots interact with PLCs, sensors, conveyors, grippers, and machines.



##  Controller Interfaces

During this learning process, I am exploring different Teach Pendant screens and controller interfaces used for:

* Program editing
* Robot positioning
* I/O monitoring
* Tool configuration
* Frame configuration
* System settings
* Alarm monitoring
* Status checking
* File management

The goal is to understand not only individual instructions but also **how the different interfaces work together during robot programming**.



##  Program Management

I am also learning how FANUC programs are:

* Created
* Edited
* Renamed
* Copied
* Loaded
* Backed up
* Transferred
* Executed

Understanding program management is essential when working with multiple robot tasks in an industrial environment.



##  Alarms & Troubleshooting

Robot programming also involves understanding controller alarms and abnormal conditions.

My learning includes:

* Reading alarm messages
* Identifying possible causes
* Checking robot status
* Understanding program errors
* Checking I/O conditions
* Resetting alarms safely
* Troubleshooting basic program issues



##  Robot Communication

I am exploring the basic concepts behind communication between the FANUC controller and external systems.

Topics include:

* Ethernet communication
* TCP/IP
* Controller communication
* External computer communication
* Data exchange
* Industrial automation interfaces

These concepts provide a foundation for integrating robots into larger automated systems.



##  External Axes

I am learning how industrial robots can work together with additional mechanical axes such as:

* Rotary tables
* Positioners
* Linear tracks
* Turntables

Understanding external axes is useful for developing more complex robotic work cells.



##  Robot Kinematics

Along with practical programming, I am studying the basic kinematics behind industrial robots.

Topics include:

* Robot coordinate systems
* Joint positions
* Cartesian positions
* Forward kinematics
* Inverse kinematics
* Robot configurations
* Denavit-Hartenberg parameters

This connects robot programming with the mechanical and mathematical concepts learned in **Mechatronics Engineering**.



##  Learning Progress

### Completed / Practiced

* [x] Teach Pendant navigation
* [x] Basic robot jogging
* [x] Creating robot programs
* [x] Basic motion instructions
* [x] Position concepts
* [x] Tool configuration
* [x] I/O concepts
* [x] Program execution

### Currently Learning

* [ ] Advanced program control
* [ ] Position Registers
* [ ] User Frames
* [ ] Advanced I/O programming
* [ ] Robot communication
* [ ] External axes
* [ ] Robot calibration
* [ ] Advanced troubleshooting



##  Practice Programs

This repository will contain small programs created while learning FANUC programming.

Examples:

```text
01_Basic_Joint_Motion
02_Linear_Motion
03_Position_Recording
04_Tool_Frame_Practice
05_User_Frame_Practice
06_Digital_Output
07_Digital_Input
08_WAIT_Instruction
09_IF_Condition
10_LOOP_Practice
11_CALL_Instruction
12_Position_Register
13_Pick_and_Place
14_Conveyor_Interaction
```

Each program will focus on **one concept at a time** so that the purpose and behavior of each instruction can be understood clearly.


##  What I Am Learning

This learning journey is helping me develop practical knowledge in:

* Industrial robot programming
* FANUC Teach Pendant operation
* Robot motion control
* Coordinate systems
* Tool and frame configuration
* I/O programming
* Program logic
* Robot troubleshooting
* Industrial communication
* Robot kinematics
* Automation system integration



##  Connection to Mechatronics

FANUC robot programming connects several areas of my **Mechatronics Engineering** studies:

```text
Mechanical Engineering
        ↓
Robot Structure & Kinematics
        ↓
Electronics
        ↓
Sensors & Actuators
        ↓
Control Systems
        ↓
Robot Programming
        ↓
Industrial Automation


Learning robot programming through the Teach Pendant helps me connect theoretical concepts with the way industrial robots are actually programmed and operated.




