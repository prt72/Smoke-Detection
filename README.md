# Smoke Detection

## About Dataset

This project uses a dataset collected with IoT devices to develop an AI-based smoke detector system.  
The dataset contains nearly 60,000 sensor readings captured at 1Hz frequency, covering multiple real-world environments including:

- Normal indoor and outdoor settings  
- Indoor wood and gas fires (firefighter training areas)  
- Outdoor wood, coal, and gas grills  
- High humidity outdoor conditions  

Each sensor reading is timestamped with UTC time to track data accurately.

---

## Problem Type

- Binary Classification  
- Target Variable: Fire Alarm (Smoke detected or not)

---

## Context

Smoke detectors sense smoke to detect fires and are generally of two types:

### Photoelectric Smoke Detector  
Uses light scattering to detect smoke particles in the air.

### Ionization Smoke Detector  
Uses ionization of air to detect smoke particles affecting the current in the detector chamber.

---

## Project Overview

Using this dataset, an AI model is trained to classify sensor readings to accurately detect smoke, aiming to improve fire alarm systems.

---

## How to Use

1. Clone this repo:  
   ```bash
   git clone https://github.com/yourusername/Smoke-Detection.git
