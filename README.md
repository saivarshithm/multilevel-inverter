# Cascaded H-Bridge Multilevel Inverter with SPWM

This repository contains the MATLAB/Simulink implementation of a **Sinusoidal Pulse Width Modulation (SPWM) based Cascaded H-Bridge (CHB) Multilevel Inverter**, developed as part of the **EE348 – Design and Development Task in Power Electronics and Drives** course at **NITK Surathkal**.

The project focuses on analyzing **power quality improvement** using multilevel inverter topologies and **LC output filtering**.

---

## 📌 Project Overview

Conventional two-level inverters suffer from high harmonic distortion, making them unsuitable for power-quality-sensitive applications.  
This project addresses the issue by implementing and comparing **3-level and 5-level cascaded H-bridge inverters** using SPWM control.

The performance is evaluated in terms of:
- Output voltage and current waveforms  
- RMS values  
- Total Harmonic Distortion (THD)  
- Effect of LC output filtering  

All analysis is carried out using **MATLAB/Simulink**.

---

## ⚙️ System Configuration

- **Inverter Topology:** Cascaded H-Bridge (3-level & 5-level)
- **Modulation Technique:** Sinusoidal PWM (SPWM)
- **Fundamental Frequency:** 50 Hz
- **DC Input Voltage:** 100 V
- **Load Type:** Resistive (10 Ω)
- **Filter:** LC Output Filter

---

## 🧪 Key Features

- SPWM pulse generation using sinusoidal reference and carrier signals  
- Modular H-bridge inverter design using MOSFET switches  
- Comparative analysis between 3-level and 5-level inverter outputs  
- Harmonic reduction using LC output filtering  
- RMS and THD measurement using Simulink analysis blocks  

---

## 📊 Results Summary

- Unfiltered inverter outputs showed high harmonic distortion  
- LC output filtering significantly improved waveform quality  
- Minimum achieved **THD ≈ 4.3%** for the 3-level inverter  
- Filtered system demonstrated clear trade-off between harmonic reduction and voltage utilization  

---

## 🛠 Tools & Software

- MATLAB  
- Simulink  
- Simscape Electrical (Power Systems)

---
