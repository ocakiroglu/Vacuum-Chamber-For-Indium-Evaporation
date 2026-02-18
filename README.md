# Indium Evaporation Vacuum Chamber

| Bottom Flange (Base) | Top Flange (Sample Holder) |
| :---: | :---: |
![Bottom Flange](images/FlangeBottom-3D.png) | ![Top Flange](images/FlangeTop-3D.png) |

## Overview
This repository contains the technical designs and specifications for a compact vacuum chamber designed for the thermal evaporation of **Indium**. The project was developed in 2017 at Bilkent University's National Nanotechnology Research Center (UNAM) for [**Strongly Correlated Materials Lab**](https://scmlab.org/). The system utilizes a vertical stack design where a quartz glass cylinder is sandwiched between two custom flanges.

### System Architecture
The chamber is designed to maintain a vacuum seal while allowing for electrical feedthroughs and vacuum pumping:

* **Chamber Body:** A quartz glass tube providing visual monitoring of the evaporation process.
* **Sealing:** Two O-rings placed between the quartz glass and the lids to ensure a leak-proof environment.
* **Top Flange:** Serves as the mounting point for the sample substrate. 
* **Bottom Flange:** The operational hub, containing ports for the vacuum pump connection and electrical feedthroughs for the heating element.

---

## Technical Specifications

### 1. Bottom Flange (Base)
The base lid is the primary interface for system utilities.
* **Dimensions:** Features a primary radius of 66.00mm and a thickness of 15.00mm
* **Mounting:** 4x M6 holes positioned at 90.0° intervals for assembly.
* **Ports:** Includes an **M16 Tapped Hole** designed for electrical feedthroughs and an **M6 Hole** designed for a small vacuum pump pipe. 

### 2. Top Flange (Sample Holder)
The top lid is designed for easy removal to access the sample.
* **Dimensions:** Matches the bottom flange with a 66.00mm radius and a thickness of 15.00mm.
* **Mounting:** 4x M6 holes aligned with the bottom flange at 90.0°.
* **Function:** Holds the sample directly above the Indium source for optimal deposition.

---

## Assembly Gallery

| Component | Technical Drawing |
| :--- | :--- |
| **Top Flange** | [View PDF](drawings/100mm-FlangetTop-Drawing.pdf) |
| **Bottom Flange** | [View PDF](drawings/100mm-FlangeBottom-Drawing.pdf) |

---

## Repository Structure
```text
├── drawings/           # PDF and AutoCAD files (ipt)
│   ├── 100mm-FlangeBottom-Drawing.pdf
│   └── 100mm-FlangetTop-Drawing.pdf
│   └── 100mm-FlangeBottom-Sketch.ipt
│   └── 100mm-FlangeTop-Sketch.ipt
├── images/             # Renders and sample device photos
│   ├── FlangeBottom-3D.png
│   └── FlangeTop-3D.png
|   └── VacuumChamber.png
|   └── VacuumChamberWithBoat.png
└── README.md
