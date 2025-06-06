# 🔌 Home Automation using ESP32, 4-Channel Relay, and Sinric Pro

## 📌 Project Overview

This project demonstrates how to build a **Smart Home Automation System** using the **ESP32 microcontroller**, a **4-channel relay module**, and **Sinric Pro** for Alexa/Google Assistant voice control and mobile app support.

With this system, you can control up to **4 electrical appliances** (lights, fans, sockets, etc.) remotely using your phone or voice commands via Alexa or Google Assistant.

---

## 🛠️ Features

- ✅ Remote control via Sinric Pro mobile app
- ✅ Voice commands through Alexa/Google Assistant
- ✅ Control 4 individual appliances
- ✅ Real-time device state synchronization
- ✅ Internet-based (IoT) control using Wi-Fi
- ✅ Secure and scalable with Sinric Pro cloud services

---

## 🔧 Hardware Requirements

| Component            | Quantity |
|----------------------|----------|
| ESP32 Dev Board      | 1        |
| 4-Channel Relay Board| 1        |
| Jumper Wires         | As needed|
| Power Supply (5V/12V)| 1        |
| Electrical appliances| 4        |

---

## 🔌 Circuit Diagram

ESP32 GPIO Pins to Relay IN Pins:
IN1 -> GPIO 16
IN2 -> GPIO 17
IN3 -> GPIO 18
IN4 -> GPIO 19

Relay VCC -> ESP32 5V
Relay GND -> ESP32 GND
