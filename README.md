# 🚀 Project POLARIS
## NASA L'SPACE Mission Concept Academy
### Lunar Permanently Shadowed Region (PSR) Rover Mission Concept

![Mission Overview](images/01-mission-overview.png)
---

## Overview

Project **POLARIS** (Polar Operations for Lunar Assessment of Resources, Ice, and Subsurface) is a conceptual robotic lunar exploration mission developed as part of NASA's **L'SPACE Mission Concept Academy**.

The mission was designed to investigate the abundance, distribution, and preservation of water-related volatiles (H₂O and OH) within Permanently Shadowed Regions (PSRs) near the lunar south pole. These regions are among the coldest environments in the Solar System and are believed to contain water ice that could support future Artemis missions and long-duration human exploration.

The mission concept followed NASA's systems engineering lifecycle and progressed through four major design reviews:

- Mission Concept Review (MCR)
- Systems Requirements Review (SRR)
- Mission Definition Review (MDR)
- Preliminary Design Review (PDR)

---

# My Roles

## Deputy Program Manager of Resources (DPMR)

As Deputy Program Manager of Resources, I contributed to the programmatic development of Project POLARIS by supporting mission planning, scheduling, and resource management activities throughout the project lifecycle.

Responsibilities included:

- Developing the Schedule Basis of Estimate (BoE)
- Developing the Cost Basis of Estimate (BoE)
- Mission schedule development
- Cost estimation support
- Procurement planning
- Resource planning
- Team coordination
- Design review preparation
- Supporting Mission Definition Review (MDR)
- Supporting Preliminary Design Review (PDR)

---

## Command & Data Handling (CDH) Engineer

As a member of the Command & Data Handling team, I designed the rover's onboard data architecture responsible for command processing, telemetry management, subsystem communications, fault management, and scientific data handling.

Responsibilities included:

- Software architecture design
- Onboard computer selection
- Data storage architecture
- Fault Detection, Isolation & Recovery (FDIR)
- Communication architecture
- Telemetry processing
- Command routing
- Direct-to-Earth communication planning
- Interface design
- Verification planning
- Trade studies

---

# Mission Objectives

The mission was designed to:

- Detect water ice (H₂O) and hydroxyl (OH) deposits
- Characterize volatile abundance
- Study volatile preservation within permanently shadowed regions
- Collect subsurface regolith samples
- Measure temperature and illumination
- Support future Artemis missions
- Improve understanding of lunar volatile evolution

---

# Mission Location

![Mission Location](images/02-mission-location.png)

Project POLARIS targeted the **Faustini-Amundsen crater region** near the Moon's south pole.

This location was selected because permanently shadowed regions (PSRs) are believed to preserve water ice and other volatile compounds due to extremely low temperatures. The rover was designed to traverse from illuminated terrain into the PSR while collecting scientific measurements at multiple locations.

---

# Concept of Operations

![Concept of Operations](images/03-concept-of-operations.png)

The Concept of Operations (ConOps) divided the mission into four operational phases:

## 1. Rover Initialization

- System activation
- Thermal system startup
- Power system checks
- Sensor calibration
- Instrument initialization

## 2. Traverse Phase

- Autonomous rover navigation
- Continuous thermal monitoring
- Illumination measurements
- Periodic telemetry transmission
- Scientific instrument preparation

## 3. Science Operations

- Spectrometer measurements
- Thermal measurements
- Illumination measurements
- 3D mapping
- Regolith sampling
- Volatile characterization

## 4. Data Processing

- Telemetry processing
- Scientific data storage
- Error correction
- Direct-to-Earth transmission
- Preparation for next science cycle

---

# Command & Data Handling Architecture

![CDH Architecture](images/04-cdh-software-architecture.png)

The Command & Data Handling subsystem served as the central processing architecture for the rover.

The Command & Data Handling (CDH) subsystem served as the central computing architecture of the rover, coordinating command execution, telemetry routing, scientific data processing, onboard storage, subsystem communication, and fault management. The architecture was designed with redundancy and fault tolerance to maximize mission reliability during autonomous lunar operations.

---
# Command & Data Handling Engineering

Beyond developing the overall software architecture, I was responsible for defining subsystem requirements, evaluating hardware tradeoffs, establishing verification strategies, and developing subsystem mass and power budgets for the rover's Command & Data Handling (CDH) subsystem.

These engineering artifacts demonstrate the systems engineering process used to mature the subsystem throughout the NASA design reviews.

---

## Requirements Engineering

![CDH Requirements](images/10-cdh-subsystem-requirements.png)

Developed subsystem requirements derived from mission-level requirements, including onboard computing, data storage, communication interfaces, radiation tolerance, fault detection, power consumption, and subsystem mass allocation.

## Verification Planning

![Verification Plan](images/11-cdh-verification-plan.png)

Developed verification methods and preliminary verification plans using inspection, analysis, and demonstration techniques to ensure each subsystem requirement could be validated during future integration and testing.

## Onboard Computer Trade Study

![OBC Trade Study](images/06-obc-trade-study.png)

Performed a weighted engineering trade study comparing candidate onboard computers based on:

- Radiation tolerance
- Flight heritage
- Processing capability
- Power consumption
- Size, Weight, Power and Cost (SWaP-C)

The selected Argotec FERMI onboard computer achieved the highest overall weighted score while satisfying the mission requirements.

## Data Storage Trade Study

![Data Storage Trade Study](images/07-data-storage-trade-study.png)

Evaluated multiple storage architectures considering:

- Reliability
- Radiation tolerance
- Capacity
- Read/write performance
- Power consumption

The selected architecture balanced redundancy, radiation tolerance, and storage capacity while remaining within subsystem constraints.

## Data Interface Trade Study

![Data Interface Trade Study](images/08-data-interface-trade-study.png)

Compared multiple spacecraft data interface architectures to determine the optimal balance between communication reliability, payload throughput, subsystem integration complexity, and SWaP constraints.

## Communications Trade Study

![Communications Trade Study](images/09-communications-trade-study.png)

Performed communications architecture trade studies comparing Direct-to-Earth communication options using weighted criteria including mission feasibility, flight heritage, data rate capability, power consumption, and overall spacecraft resource utilization.

## CDH Subsystem Mass & Power Budget

![Subsystem Budget](images/12-cdh-subassembly-budget.png)

Developed preliminary subsystem mass, dimensions, and power budgets for each CDH subassembly to ensure compliance with spacecraft-level Size, Weight, and Power (SWaP) constraints.

---
# NASA Systems Engineering Reviews

Project POLARIS followed NASA's systems engineering lifecycle and progressed through four formal design reviews.

| Review | Purpose | My Contributions |
|---------|----------|----------------|
| Mission Concept Review (MCR) | Established mission concept and science objectives | Supported early mission planning and CDH architecture |
| Systems Requirements Review (SRR) | Developed subsystem requirements and trade studies | Designed CDH architecture and subsystem interfaces |
| Mission Definition Review (MDR) | Matured mission architecture, schedule, procurement, and cost | Developed the Schedule Basis of Estimate (BoE) and Cost Basis of Estimate (BoE) as DPMR |
| Preliminary Design Review (PDR) | Finalized preliminary spacecraft design | Completed CDH architecture, verification planning, and systems integration support |

Throughout these reviews our team developed:

- Science Traceability Matrix (STM)
- Mission Requirements
- Subsystem Requirements
- Trade Studies
- Risk Analysis
- Failure Mode & Effects Analysis (FMEA)
- Verification Plans
- Procurement Plans
- Cost Estimates
- Mission Schedule
- Interface Control Documentation

# Project Management Contributions

As Deputy Program Manager of Resources, I worked on several programmatic aspects of the mission in addition to my technical responsibilities.

Major contributions included:

- Schedule Basis of Estimate (BoE)
- Cost Basis of Estimate (BoE)
- Integrated mission schedule
- Resource planning
- Procurement planning
- Cost analysis
- Mission planning
- Schedule development
- Review preparation
- Design review coordination

---

# Mission Schedule

![Mission Schedule](images/05-mission-schedule.png)

The mission schedule followed NASA's mission lifecycle from preliminary design through launch, surface operations, and mission closeout.

Major milestones included:

- Preliminary Design Review (PDR)
- Critical Design Review (CDR)
- Hardware integration
- System Integration Review (SIR)
- Operational Readiness Review (ORR)
- Launch
- Lunar landing
- Science operations
- Mission closeout

---

# Organization

## Mission Organization
Project POLARIS was developed by an interdisciplinary engineering team consisting of:

- Systems Engineering
- Project Management
- Mechanical Engineering
- Electrical Engineering
- Thermal Engineering
- Payload Engineering
- Science Division
- Program Analysis
- Mission Assurance

Working in this environment provided experience collaborating across multiple engineering disciplines while following NASA systems engineering practices.

---

# Technical Skills Demonstrated

### Systems Engineering

- Requirements Engineering
- Science Traceability Matrix
- Trade Studies
- Interface Control
- Verification Planning
- Risk Analysis
- FMEA

### Spacecraft Engineering

- Command & Data Handling
- Software Architecture
- Telemetry
- Data Storage
- Fault Detection & Recovery
- Communications
- Spacecraft Interfaces

### Project Management

- Schedule Development
- Cost Estimation
- Schedule Basis of Estimate
- Cost Basis of Estimate
- Resource Planning
- Procurement Planning
- Team Coordination

---

# Tools & Technologies

- Systems Engineering
- NASA L'SPACE
- Microsoft Visio
- Draw.io
- Lucidchart
- Microsoft Project
- Excel
- PowerPoint

---

# Lessons Learned

Project POLARIS provided hands-on experience applying NASA systems engineering practices to the development of a complete lunar mission concept.

The project strengthened my experience in:

- Multidisciplinary engineering collaboration
- Systems engineering methodology
- Technical documentation
- Requirements development
- Engineering trade studies
- Technical communication
- Spacecraft subsystem integration
- Program planning and resource management

Working simultaneously as a Command & Data Handling Engineer and Deputy Program Manager of Resources provided experience balancing technical engineering decisions with project management responsibilities while participating in NASA-style design reviews.

---

# Certificate

NASA L'SPACE Mission Concept Academy Certificate of Completion

![NASA L'SPACE Certificate](images/06-certificate.jpg)

---

# Repository Contents

```
NASA-Polaris-Lunar-Rover
│
├── README.md
├── images/
│   ├── 01-mission-overview.png
│   ├── 02-mission-location.png
│   ├── 03-concept-of-operations.png
│   ├── 04-cdh-software-architecture.png
│   ├── 05-mission-schedule.png
│   ├── organization-chart.png
│   └── 06-certificate.pdf
```

---

# About NASA L'SPACE

NASA's L'SPACE Mission Concept Academy is a workforce development program that introduces students to NASA's systems engineering process by guiding multidisciplinary teams through the complete formulation of a conceptual space mission. Participants develop mission concepts using industry-standard engineering practices while progressing through formal NASA design reviews including Mission Concept Review (MCR), Systems Requirements Review (SRR), Mission Definition Review (MDR), and Preliminary Design Review (PDR).

---

## Connect With Me

Thank you for taking the time to review Project POLARIS.

If you have questions about this project or would like to discuss engineering opportunities, please feel free to reach out.

- LinkedIn: [https://www.linkedin.com/in/nehoraibachur/](https://www.linkedin.com/in/nehoraibachur/)
- GitHub: [https://github.com/nehoraibar](https://github.com/nehoraibar)
- Email: nehoraibar@gmail.com
