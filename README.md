# -RFID-Based-Passport-Verification-System-using-8051-Microcontroller
This project implements an RFID-based passport verification system that securely authenticates passport holders. The system uses an EM-18 RFID reader interfaced with an 8051 microcontroller to read passport details stored in RFID tags and compare them with stored records. The verification result is displayed on a 16×2 LCD screen.

✅ **Automation** – Eliminates manual passport verification
✅ **Security** – Prevents forgery and unauthorized access
✅ **Efficiency** – Provides real-time, reliable verification


## 🛠️ Components & Tools

* **Hardware**: 8051 Microcontroller, EM-18 RFID Reader, RFID Tags, 16×2 LCD, Power Supply, Potentiometer, Jumper Wires
* **Software**: Keil µVision (C/ASM programming), Proteus (simulation)

## ⚡ Features

* Reads and verifies RFID passport details
* Compares received data with stored records
* Displays **“Passport Verified”** or **“Invalid Passport”** on LCD
* Simulation in **Proteus** and hardware prototype tested
* Can be extended to **access control, library management, toll collection, hospital patient management**, and more

## 💻 Working

1. User swipes passport (RFID tag) on RFID reader
2. 8051 receives data and processes it
3. System compares received details with stored records
4. LCD displays verification result (Valid/Invalid)



## 📂 Project Structure

```
├── Code/
│   ├── rfid_passport_verification.asm   # 8051 assembly code
│   └── rfid_passport_verification.c     # (optional C version if implemented)
├── Simulation/
│   └── Proteus files
├── Hardware/
│   └── Circuit diagram + setup images
└── README.md
```
## 🚀 Challenges Faced

* RFID tag compatibility issues
* Efficient microcontroller programming (interrupts, timers)
* Data parsing and record matching
* LCD integration and stable power supply

## 📌 Applications

* Passport & border security
* Access control systems
* Library management
* Toll collection & vehicle ID
* Hospital patient management
* Event ticketing & crowd control

---

## 🏆 Conclusion

This project demonstrates the **integration of RFID with microcontroller-based verification** to provide a secure and efficient passport authentication system. It shows how embedded systems and RFID can be combined for **real-world security applications**.

