# 1994 Toyota 4Runner A340 Transmission Control Unit (TCU)

Custom standalone Transmission Control Unit (TCU) for a **1994 Toyota 4Runner** equipped with the **A340 automatic transmission**.

This project focuses on replacing or supplementing the factory transmission control logic using a microcontroller-based solution, with an emphasis on reliability, tunability, and serviceability.

---

## Project Goals

- Standalone control of the A340 transmission
- Configurable shift logic and line pressure control
- Simple, serviceable hardware using common components
- Clear separation between firmware, hardware, and documentation
- Designed for off-road and modified drivetrain applications

---

## Current Status

**Early development**

- Repository structure initialized
- Firmware and hardware architecture planning
- No production-ready firmware yet

---

### Folder Descriptions

- **firmware/**  
  Arduino-based firmware for transmission control logic, solenoid control, and testing.

- **hardware/**  
  Mechanical and electrical design files including:
  - STL files for 3D-printed components
  - STEP files for CAD reference
  - Drawings and diagrams

- **docs/**  
  Documentation such as wiring diagrams, pinouts, calibration notes, and design decisions.

---

## Transmission Overview

- **Transmission:** Toyota A340
- **Vehicle:** 1994 Toyota 4Runner
- **Control Focus:**
  - Shift solenoids
  - Line pressure control
  - Input signals (TPS, RPM, vehicle speed, temperature)

---

## Design Philosophy

- Keep the system simple and debuggable
- Avoid unnecessary complexity or black-box behavior
- Favor mechanical and electrical robustness over features
- Support incremental development and testing

---

## Planned Features

- Adjustable shift points
- PWM-controlled line pressure
- Manual and automatic operating modes
- Data logging for tuning and diagnostics
- Modular firmware design

---

## Disclaimer

This project is **experimental** and intended for educational, off-road, and research use.  
Improper configuration may cause transmission damage. Use at your own risk.

---

## License

License to be determined.
