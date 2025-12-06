# 🚗✨ **Wi-Fi Controlled IoT Car using ESP32 & Blynk**

### *A Smart, Mobile-Controlled Robotic Car Powered by IoT*

<p align="center">
  <img src="images/car-front-view.jpg" width="400px" />
</p>

---

## 🚀 **Overview**

This project showcases a fully functional **IoT-enabled robotic car** built using the **ESP32**, **L293D motor driver**, and the **Blynk IoT platform**.
The car can be controlled **wirelessly from any smartphone**, offering real-time navigation, speed control, and smooth motion via Wi-Fi.

Designed for learning, prototyping, and IoT experimentation.

---

## ⚙️ **Tech Stack**

| Category            | Tools/Hardware    |
| ------------------- | ----------------- |
| **Microcontroller** | ESP32 Dev Board   |
| **Motor Driver**    | L293D             |
| **Platform**        | Blynk IoT         |
| **IDE**             | Arduino IDE       |
| **Communication**   | Wi-Fi (802.11)    |
| **Control**         | PWM Motor Control |

---

## ⭐ **Features**

✔ Real-time control via **Blynk mobile app**
✔ Forward, backward, left & right navigation
✔ **PWM-based** smooth speed variation
✔ Low-latency Wi-Fi communication
✔ Modular and expandable design
✔ Easy to build & experiment with

---

## 🛠️ **Hardware Components**

* ESP32 Development Board
* L293D Motor Driver
* Dual DC Motors
* Robot Chassis
* Wheels
* Battery Pack
* Jumper Wires
* Optional: Power Switch

> All components used are inexpensive and easily available.

---

## 🔌 **Circuit Wiring**

Add wiring diagram in:
`/circuit-diagrams/wiring-diagram.png`

**Basic Wiring Layout:**

```
ESP32 GPIO → L293D IN1–IN4  
ESP32 PWM → Enable Pins  
5V / Vin → Motor Driver Supply  
GND → Common Ground
```

---

## 📱 **Blynk IoT Dashboard Setup**

Create the following widgets in Blynk:

| Widget   | Type   | Virtual Pin | Function          |
| -------- | ------ | ----------- | ----------------- |
| Forward  | Button | V1          | Move forward      |
| Backward | Button | V2          | Move backward     |
| Speed    | Slider | V3          | PWM speed control |

Upload a screenshot in `/images/blynk-dashboard.jpg`.

---

## 💻 **Source Code**

The ESP32 code is stored in:

```
/src/main.ino
```

### 🔧 Key Functionalities:

* Wi-Fi authentication
* Blynk IoT communication
* Motor direction control
* PWM speed modulation

---

## 📸 **Project Images**

Add pictures of your actual robot:

```
images/car-front-view.jpg
images/car-side-view.jpg
images/blynk-dashboard.jpg
```

<p align="center">
  <img src="images/car-side-view.jpg" width="350px" />
</p>

---

## 🧠 **How It Works**

1. ESP32 connects to Wi-Fi
2. Blynk app sends virtual pin commands
3. ESP32 processes commands
4. L293D activates motors accordingly
5. PWM adjusts motor speed in real time

---

## 🧪 **How to Use**

1. Clone this repository
2. Open `main.ino` in Arduino IDE
3. Install required libraries:

   * Blynk
   * WiFi
4. Insert Wi-Fi SSID, password, and Blynk auth token
5. Upload code to ESP32
6. Open Blynk → Run dashboard → Control the car!

---

## 📚 **Libraries Used**

```text
BlynkSimpleEsp32.h
WiFi.h
```

---

## 🔮 **Future Improvements**

* 🔷 Add ultrasonic sensor for obstacle avoidance
* 🔷 Add line-tracking using IR sensors
* 🔷 Add camera streaming for FPV control
* 🔷 Add Bluetooth fallback mode

---

## 📝 **Project Folder Structure**

```
iot-car-esp32-blynk/
│
├── src/
│   └── main.ino
│
├── circuit-diagrams/
│   └── wiring-diagram.png
│
├── images/
│   ├── car-front-view.jpg
│   ├── car-side-view.jpg
│   └── blynk-dashboard.jpg
│
├── components/
│   └── parts-list.md
│
└── README.md
```

---

## ❤️ **Developed By**

**Akash Roy**
Embedded Systems & IoT Enthusiast
📧 [aroy50809@gmail.com](mailto:aroy50809@gmail.com)

---

## ⭐ **Support This Project**

If you like this project, please ⭐ **star the repository** — it motivates future updates!



Just tell me **which one next!**
