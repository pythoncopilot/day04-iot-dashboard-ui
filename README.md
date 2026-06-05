# Day 4 - Smart Home IoT Dashboard UI

## Objective
Design a realistic smart home IoT dashboard that simulates control of multiple rooms including living room, bedroom, kitchen, bathroom, lounge, and garage using an interactive web interface.

---

## Description
This project simulates a professional smart home IoT control system interface where multiple rooms in a house are individually monitored and controlled through a centralized dashboard. Each room contains independent smart devices such as lights, fans, and appliances, which can be toggled or adjusted through interactive UI elements like buttons and sliders. The dashboard is structured to represent a real-world IoT home automation system where each zone operates independently but is managed under a unified control panel. This layout forms the foundation for future integration with Arduino-based sensors and actuators through Python and IoT communication protocols.

---

## Components Used
- HTML
- CSS
- JavaScript
- Web Browser
- VS Code (optional Live Server)

(No hardware required for this stage)

---

## Working Principle
1. Smart home layout is divided into rooms (zones)
2. Each room has independent device controls
3. User interacts with switches and sliders
4. UI updates reflect device state changes instantly
5. Future version will connect to real IoT devices via backend

---

## Code Summary
- HTML creates room-based layout structure
- CSS builds smart home grid UI
- JavaScript handles:
  - room-wise device control
  - state toggling (ON/OFF)
  - intensity/speed adjustments
  - real-time status updates

---

## Expected Output
- Smart home dashboard layout
- Rooms:
  - Living Room
  - Bedroom
  - Kitchen
  - Bathroom
  - Lounge
  - Garage
- Controls:
  - Lights ON/OFF
  - Fan speed slider
  - Appliance toggles
- Real-time UI state updates

---

## Notes
This dashboard is designed as a professional IoT frontend system that will later be connected to Arduino and Python backend for real device control.
