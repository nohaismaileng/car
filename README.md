# 🤖 Multi-Mode Mobile Robot (Arduino)

A collection of mobile robot implementations including obstacle avoidance, line following, and manual control using Arduino.

---

## 📌 Overview

This repository contains multiple robotic systems designed for different navigation and control tasks.
Each module demonstrates a specific functionality that can be used independently or integrated into a full autonomous robot.

---

## 🚀 Features

* 🚧 Obstacle Avoidance Robot (Ultrasonic-based)
* ➖ Line Follower Robot (IR sensors)
* 🎮 Manual Direction Control (Serial/Bluetooth)
* 🔥 Fire Detection with Alarm System
* 🧠 Modular design for easy integration

---

## 📂 Project Structure

```text
car/
│
├── Obstacle avoiding robot/
│   ├── code
│   └── circuit.png
│
├── line-follower/
│   ├── code
│   └── line-follower-circuit.png
│
├── direction/
│   ├── code
│   └── direction.circuit.png
│
├── main/
│   └── integrated system (future work)
│
├── test/
│   └── motor control experiments
│
└── circuit.png
```

---

## ⚙️ How It Works

### 🚧 Obstacle Avoidance

* Uses ultrasonic sensor to detect distance
* Avoids obstacles automatically

### ➖ Line Follower

* Uses IR sensors to follow a predefined path

### 🎮 Direction Control

* Controlled manually via serial commands
* Supports forward, backward, left, right, and stop

### 🔥 Fire Detection

* Uses flame sensor + servo scanning
* Activates buzzer when fire is detected

---

## 🔌 Hardware Components

* Arduino UNO / Nano
* Ultrasonic Sensor (HC-SR04)
* IR Sensors
* Flame Sensor
* Servo Motor
* L298N Motor Driver
* DC Motors
* Buzzer
* Power Supply

---

## 🧠 Applications

* Robotics learning projects
* Autonomous navigation systems
* Smart safety robots
* Industrial inspection prototypes

---

## 🔧 Future Improvements

* Integrate all modes into one smart system
* Add Bluetooth / WiFi control
* Implement AI-based navigation
* Add camera for vision-based tracking

---

## 👩‍💻 Author

Eng Noha
Embedded Systems & Robotics Engineer

---

## ⭐ Notes

This project demonstrates multiple robotics concepts and serves as a foundation for building advanced intelligent robots.
