---
title: "Attitude Determination and Control Subsystem "
excerpt: "Attitude Determination and Control Subsystem <br/><img src='/images/500x300.png'>"
collection: portfolio
---

# Attitude Determination and Control System (ADCS)  

The **Attitude Determination and Control System (ADCS)** is a critical subsystem responsible for managing a satellite's orientation and stabilization. The ADCS ensures the satellite maintains its desired attitude through precise determination and control, accommodating mission objectives and operational constraints.  

## System Components  

The ADCS consists of the following components:  

- **Sensors:** These include gyroscopes, magnetometers, sun sensors, and star trackers. Sensors are modeled to incorporate realistic noise profiles to simulate performance in space environments.  
- **Actuators:** The primary actuation method uses reaction wheels, but additional methods like magnetorquers and thrusters for attitude adjustments may be incorporated.  
- **Control Algorithms:** These process sensor data and generate control signals to achieve desired satellite orientation, encompassing functions such as attitude determination and control mode transitions.  

## System Requirements  

The ADCS simulation is designed to meet the following key requirements:  

- Simulate sensor inputs (e.g., sun sensors, magnetometers) with the flexibility to add more sensors.  
- Determine and propagate the satellite's attitude while accounting for disturbances.  
- Include reaction wheel spin-up time and modularity for flexible integration and subsystem testing.  
- Model control modes such as orientation, tracking, and a 180-degree slew maneuver.  

## Data Interactions with Other Subsystems  

The ADCS interacts with other satellite subsystems to ensure mission success:  

- **Power Subsystem:** Supplies power usage data from sensors, actuators, and processing units.  
- **Thermal Subsystem:** Supplies orientation data (Euler angles) to calculate solar heating effects.  
- **Orbital Determination and Control Subsystem:** Supplies orientation data and receives orbital elements, position, and velocity vectors for external disturbance calculations.  
- **Telemetry Subsystem:** Supplies orientation data and receives transmission parameters for optimized communication.  

## System Architecture  

Below is the ADCS system diagram illustrating the relationships between sensors, actuators, control algorithms, and data interactions with other subsystems.  

![ADCS Subsystem Architecture](placeholder-for-diagram.png)  

*Figure 1: ADCS Subsystem Architecture*  

> *Note: Replace the above placeholder with the actual system diagram when available.*  

## Conclusion  

The ADCS is pivotal in maintaining the satellite's stability and meeting mission objectives through precise orientation control. The modularity and adaptability of the system ensure seamless integration and robust performance throughout all mission phases.  
