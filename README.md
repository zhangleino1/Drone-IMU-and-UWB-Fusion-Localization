# Drone IMU and UWB Fusion Localization

## Project Overview
This repository implements a robust localization system for drones by fusing data from Inertial Measurement Units (IMU) and Ultra-Wideband (UWB) technology. The fusion algorithm combines the high-frequency motion data from IMUs with the accurate positioning capabilities of UWB to achieve precise indoor and outdoor drone localization.

## Key Features
- Integration of IMU sensor data (accelerometer, gyroscope) for short-term motion tracking
- UWB-based ranging and positioning for absolute location reference
- Extended Kalman Filter (EKF) implementation for sensor fusion
- Real-time pose estimation with low latency
- Drift compensation mechanism for long-duration flights


## Technical Background
Indoor drone localization presents significant challenges due to the unavailability of GPS signals. This project addresses these challenges by implementing a multi-sensor fusion approach:
- IMU provides high-frequency (100-200Hz) orientation and acceleration data
- UWB provides accurate distance measurements to fixed anchors (10-20Hz)
- The fusion algorithm combines these complementary data sources to achieve reliable 3D positioning

## Applications
- Indoor autonomous navigation
- GPS-denied environments
- Precision drone operations
- Swarm robotics research
- Educational platforms for robotics and control systems

## Dependencies
- Python implementation
- Compatible with common IMU sensors (MPU9250, BMI088, etc.)
- Works with UWB modules (DWM1000, DWM3000, etc.)

## Installation & Usage
See the documentation for detailed setup and implementation instructions.

## Contributing
Contributions to improve the fusion algorithm, add support for additional sensors, or enhance the documentation are welcome.
