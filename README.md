# RFID-Based Smart Locking System

### ESP32-Based Electronic Access Control Using RFID Authentication

An embedded security system that uses RFID authentication to control an electromagnetic locking mechanism.

---

## 📌 Project Overview

The RFID Smart Locking System is an embedded electronics project developed using an ESP32 microcontroller and an RC522 RFID reader.

The system uses RFID-based identification to control access through an electromagnetic locking mechanism.

The project combines embedded programming, RFID communication and electronic hardware integration to demonstrate an automated access control system.

## 🎯 Objectives

- Develop an RFID-based access control system.
- Interface an RC522 RFID reader with an ESP32.
- Implement RFID identification and authentication.
- Control an electromagnetic locking mechanism.
- Integrate electronic hardware for automated locking.

## ⚙️ Components Used

| Component | Application |
|---|---|
| ESP32 | Main microcontroller |
| RC522 RFID Module | RFID card/tag identification |
| RFID Cards/Tags | User identification |
| Electromagnetic Lock | Physical locking mechanism |
| TIP122 Transistor | Switching control |
| Relay Module | Lock control |
| Flyback Diode | Inductive voltage protection |
| Power Supply | Circuit power |

## 🧩 System Architecture

The system follows an RFID authentication workflow:

1. An RFID card or tag is presented to the reader.
2. The RC522 module reads the RFID information.
3. The ESP32 processes the received information.
4. The authentication logic determines whether access is authorised.
5. The electronic locking mechanism is controlled accordingly.

## 🔧 Hardware Implementation

The hardware consists of an ESP32 connected to an RC522 RFID reader and an electromagnetic locking mechanism.

A switching circuit involving a TIP122 transistor and relay module is used as part of the locking control arrangement.

A flyback diode is included to protect the circuit against inductive voltage spikes.

## 💻 Software Implementation

The ESP32 handles RFID communication and access control logic.

The software is responsible for reading RFID information, processing authentication and controlling the locking hardware.

## 🚀 Future Improvements

- Add additional authentication methods.
- Improve access management.
- Introduce access logging.
- Develop a monitoring interface.
- Improve overall security and reliability.

## 👥 Project Information

**Project Type:** Academic Embedded Systems Project

**Course:** Engineering Electromagnetics

**Development:** 2025–2026

**Platform:** ESP32

**Contribution:** Worked on ESP32 programming, software testing, debugging and hardware integration.

---

*This project demonstrates the integration of RFID technology, embedded programming and electronic access control.*
