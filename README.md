# 👓 Smart Eyeglasses for Driving Safety

> An embedded anti-microsleep system designed to detect prolonged eye closure and alert drivers through vibration and sound.

---

## 🚗 Project Overview

**Smart Eyeglasses** is an embedded safety system developed to help reduce the risk of drowsy driving and microsleep.

The system uses an **IR sensor** to monitor the driver's eyelid condition. When prolonged eye closure is detected, the system activates a **vibration motor** and **buzzer** to alert the driver and regain their attention.

The prototype was developed using an **Arduino Uno** as the main microcontroller.

---

## ⚙️ System Architecture

```text
          IR SENSOR
              │
              ▼
        ┌─────────────┐
        │ Arduino Uno │
        └──────┬──────┘
               │
        ┌──────┴──────┐
        ▼             ▼
   VIBRATION        BUZZER
     MOTOR           ALERT
        │             │
        └──────┬──────┘
               ▼
         DRIVER ALERT
