# Design and Development of a Lab-Scale Filament Winding Machine

![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)

A desktop filament winding machine designed in **CAD** for manufacturing composite parts, featuring an **Arduino-controlled** system for precise, automated winding. This project was developed as part of the Design Practicum course at IIT Mandi.

---

## CAD Model of the Filament Winder
<img width="832" height="823" alt="image" src="https://github.com/user-attachments/assets/a640cd48-7eaf-4adb-a4ef-f114a1a7ee5f" />


## 📖 Abstract

Filament winding is a key manufacturing process for creating lightweight, high-strength, and corrosion-resistant composite materials used in industries like aerospace, automotive, and renewable energy. This project covers the complete design and development of a compact, lab-scale filament winding machine suitable for educational and R&D purposes. The final design integrates mechanical principles with an Arduino-based mechatronic system to achieve automated and precise winding patterns.

## ⚙️ Key Features & Specifications

#### Features
- **Automated Winding:** An Arduino-controlled linear actuator enables precise and repeatable helical winding patterns.
- **Detailed CAD Design:** The entire assembly was modeled in 3D CAD, with 2D manufacturing drawings produced for all components.
- **Cost-Effective Construction:** Utilizes a wooden frame and readily available components to create a functional prototype on a budget.
- **Optimized for Precision:** Features a moving resin bath instead of a moving mandrel to ensure higher consistency and accuracy in the winding process.

#### Specifications
| Parameter | Value |
| :--- | :--- |
| **Setup Dimensions** | 60cm x 30cm x 30cm |
| **Max Product Length**| 15cm |
| **Max Product Radius**| 2.5cm |
| **Reinforcement Fiber** | Glass Fiber |
| **Matrix Material** | Epoxy Resin |
| **Frame Material** | Wood |

## 🛠️ Design & Methodology

The machine was developed following a systematic engineering design process: understanding the problem, identifying potential solutions, benchmarking against commercial products, detailed design, and finally, manufacturing and testing.

### Mechanical Design
A key design feature is the **linearly moving resin bath**, which travels along a stationary **rotating mandrel**. This approach enhances the precision of the winding pattern. The resin bath contains a series of rods to maintain proper fiber tension and ensure thorough impregnation with the heated epoxy. All parts were modeled in SolidWorks to ensure proper fit and function before manufacturing.

## 2D Manufacturing Drawing
<img width="881" height="649" alt="image" src="https://github.com/user-attachments/assets/d4b4ef35-1611-4113-9117-f6089f01d528" />


### Electronic Control System
The automation is achieved using a simple yet robust mechatronic system. An **Arduino Uno** acts as the microcontroller, sending signals to an **LN298N Motor Driver** which powers the **Linear Actuator** responsible for the resin bath's precise horizontal movement.

## Circuit Diagram
<img width="547" height="398" alt="image" src="https://github.com/user-attachments/assets/5114cdc0-982c-4118-83f5-4dd3f26d9c57" />


## 🔩 Technologies & Components

- **Software:** SolidWorks (CAD), Arduino IDE
- **Hardware:** Arduino Uno, LN298N Motor Driver, Linear Actuator, DC Motor
- **Materials:** Plywood, Aluminum Rods, Glass Fiber, Epoxy Resin

## 🚀 Setup and Use

1.  Assemble the mechanical frame and components according to the CAD drawings.
2.  Wire the electronic components (Arduino, motor driver, actuator) as per the circuit diagram.
3.  Upload the control code (`.ino` file) to the Arduino Uno.
4.  Prepare the epoxy resin and thread the glass fiber through the resin bath.
5.  Secure the mandrel and begin the automated winding process.

## 📄 License
This project is licensed under the **MIT License**.
