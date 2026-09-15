# Smart-Seating-Arrangement-System-using-ESP32


**Duration:** Sept 2025 – Nov 2025  
**Domain:** Embedded Systems / IoT  
**Platform:** ESP32  
**Sensors:** IR Sensors  

## 📌 Project Overview
This project implements a **smart seating arrangement system** using an ESP32 microcontroller and IR sensors to detect **seat-level occupancy**. Each seat is monitored independently, avoiding conventional entry/exit counting techniques. The real-time seating status is displayed through a **web-based interface hosted on the ESP32**.

## 🎯 Objectives
- Detect occupied and vacant seats individually
- Avoid inaccurate entry/exit counting methods
- Provide real-time visualization through a web interface
- Gain hands-on experience with ESP32, GPIO interfacing, and IoT systems

## 🛠 Hardware Components
- ESP32 Development Board
- IR Sensors (one per seat)
- Breadboard & Jumper Wires
- 5V / 3.3V Power Supply

## 🔌 Pin Configuration
| Seat | IR Sensor Pin | ESP32 GPIO |
|----|--------------|------------|
| Seat 1 | OUT | GPIO 18 |
| Seat 2 | OUT | GPIO 19 |
| Seat 3 | OUT | GPIO 21 |
| Seat 4 | OUT | GPIO 22 |

(Expandable for N seats)

## ⚙️ Working Principle
- Each seat is assigned one IR sensor.
- IR sensor output changes based on seat occupancy.
- ESP32 reads GPIO states and determines seat status.
- ESP32 hosts a local web server.
- Seating status is updated and displayed in real-time on a web page.

## 🌐 Web Interface
- Hosted directly on ESP32
- Displays **Occupied / Vacant** status for each seat
- Auto-refresh / dynamic update using JavaScript

## 🧪 Testing & Validation
- Tested under multiple seating combinations
- Verified individual seat detection accuracy
- Ensured stable web server response
- Confirmed no dependency on entry/exit logic

## 📈 Outcomes
- Accurate seat-level occupancy detection
- Real-time IoT-based monitoring
- Improved understanding of:
  - ESP32 GPIO interfacing
  - IR sensor integration
  - Embedded web servers
  - Practical IoT system design

## 🚀 Future Enhancements
- Wi-Fi cloud dashboard (Firebase / Thingspeak)
- Mobile app integration
- Seat count analytics
- Power optimization using deep sleep

## 👤 Author
**Pradeep Swami**  
B.Tech Electrical Engineering  
IIT Indore  

## 📜 License
This project is licensed under the MIT License.