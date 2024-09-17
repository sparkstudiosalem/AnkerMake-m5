# AnkerMake m5 Standard Operating Procedures (SOP)

## Please read this document in its entirety to learn how to use the AnkerMake m5 3D printer safely and responsibly.
-------------------------------
This document provides step-by-step instructions for operating the AnkerMake m5 3D printer utilizing OrcaSlicer to ensure safe and efficient printing and outlines any rules and procedures that must be followed by any user.

This document will cover:

* Storage and use
* Material-specific machine configurations
* Accessing print profiles and webUI from OctoPrint
* Preparing the printer for print jobs
* Printer-specific features & hazards
* Rules & Misc. Procedures
----------
  Firmware and additional documentation can be found on the [AnkerMake m5 Product Page](https://www.ankermake.com/products/m5?variant=42744298373269&discount=WS7DV2ZTWD0G).
  
  Slicer documentation can be found on the [AnkerMake Studio Page](https://www.ankermake.com/ankermake-studio).

-------------

## Storage and Use
While the printer is not in use, it should be stored with the power switched off and all tools and materials properly organized. The power switch is located at the rear of the printer near the power input.

Only authorized users should operate the AnkerMake m5 3D printer. Any unauthorized users must be supervised by an authorized user.

## Material-Specific Machine Configuration
The AnkerMake m5 works with a range of materials, but machine setup varies depending on the material.

### Low-Temperature Materials
For materials like PLA, PETG, and TPU, ensure good airflow during printing. Keep the printer in a well-ventilated area, and utilize part cooling fans. These filaments are less prone to warping and can be printed with the bed at lower temperatures.

Low-temp filaments include:
* PLA
* PETG
* TPU

### High-Temperature Materials
It is not recommended to print High temp, "Engeneering materials" on the AnkerMake m5 due to its open build platform and PTFE-Lined hotend.

High-temp filaments include:
* ABS
* ASA
* PC (Polycarbonate)
* Nylon

### Abrasive Materials
It is not recommended to print abrasive filament on the AnkerMake m5 at this time due to its extrude, hotend, and nozzle construction. 

## Accessing Print Profiles and WebUI from OctoPrint
AnkerMake Studio has been pre-configured on the designated 3D printing computer at Spark Studio. It provides easy slicing, as well as file transfer and remote print monitoring via their UI, eliminating the need for SD cards or USB drives. Though if you want to utilize the slicer from your own computer, you will need a USB Flash drive to transfer g-code files.

AnkerMake Studio allows for monitoring and controlling print jobs via an application interface. The AnkerMake m5 profile can be accessed from AnkerMake Studio and sent to the printer wirelessly. AnkerMake Studio can also be downloaded and configured on personal computers if preferred.

## Preparing the Printer for Print Jobs and Removing Prints
Before printing, the build surface must be properly prepared. The AnkerMake m5 uses a removable magnetic build plate that may need coating with glue stick or hairspray, depending on the filament being used. The bed is made of PEI Coated spring steel.

Preheat the bed and extruder according to the material’s specifications. AnkerMake Studio provides preset profiles with appropriate temperatures, but users should verify settings before printing.

Prints should only be removed from the build surface after the bed has cooled down to ambient temperature. For best adhesion, clean the bed every few prints with isopropyl alcohol, and perform a deep cleaning with soap and water when necessary.

## Printer-Specific Features & Hazards
The AnkerMake m5 is equipped with a heated bed that can reach up to 120°C (212°F). Caution should be exercised when operating or working near the bed, as it can cause burns. Additionally, the stepper motors and belts can move quickly, so avoid placing hands or objects near the moving parts during operation.

## Other Rules & Misc. Procedures
* No part of the AnkerMake m5 (firmware, software, hardware) should be modified without explicit permission from the designated committee or tool director.
* Modifying the printer may void the warranty as per Anker's guidelines.

## Other Documentation
Further documentation can be found in [Links.txt]
