JointSense System Architecture

Overall Flow

Human Movement
      ↓
MPU6050 IMU
      ↓
I2C
      ↓
ESP32
      ↓
Sensor Processing
      ↓
Feature Extraction
      ↓
Movement Analysis
      ↓
User Interface

ECE Concepts

1. Sensing

The IMU captures motion-related acceleration and rotational information.

2. Communication

The sensor can communicate with the ESP32 through I2C.

3. Embedded Processing

The ESP32 can acquire and process the sensor data.

4. Signal Processing

Raw sensor measurements can be filtered and converted into useful features.

5. Digital Hardware

Selected processing operations can later be described using Verilog/SystemVerilog.

6. FPGA

The RTL design can eventually be tested on FPGA hardware.
