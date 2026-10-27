# Awesome OpenAgri [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of open-source tools, platforms, datasets, and hardware outcomes developed within the [OpenAgri](https://github.com/openagri-eu) project.

*Inspired by [Bryce Johnston](https://github.com/brycejohnston)'s [`awesome-agriculture`](https://github.com/brycejohnston/awesome-agriculture) project. A special thanks to Bryce for cultivating open-source curation in agtech!*

The OpenAgri initiative focuses on empowering sustainable, data-driven, and open agriculture. 
This repository serves as a central index for all open-source deliverables, including software, hardware and datasets produced by the OpenAgri tech providers working on the various pilots of the project. 
You can read more about the OpenAgri pilots here https://horizon-openagri.eu/sustainable-innovation-pilots/ 
and here:  https://horizon-openagri.eu/external-sips/


---

## Contents

- [Platforms & Software](#platforms--software)
- [Data Models & APIs](#data-models--apis)
- [Datasets & AI Models](#datasets--ai-models)
- [Hardware & IoT Specs](#hardware--iot-specs)
- [Documentation](#documentation)
- [Standards & Interoperability](#standards--interoperability)
- [Contributing](#contributing)

---

## Platforms & Software

- [OpenAgri Prescription Map Editor (EDEN)](https://github.com/Eden-Library-AI/openagri_prescription_map_editor) - Creates, edits, and optimizes field-specific prescription maps for variable-rate applications.
- [Visit Creation Algorithm](https://github.com/e-peltier18/Animal-visit-reporting/tree/main) - Transforms RFID animal detections into behavioural insights for herd and grazing management.
- Colorado Potato Beetle Detection Engine - Detects Colorado potato beetles in field images to support timely interventions.
- Visualisation Framework for Colorado Beetle detections - Presents beetle-detection results as interactive monitoring views for pest surveillance.
- [OpenAgri Smart Irrigation Controller](https://gitlab.pcss.pl/openagri/openagri-smartirrigationcontroller) - Combines real-time sensor data, automation, and remote monitoring for precision irrigation.
- [Irrigation algorithms for potatoes and sugar beets](https://gitlab.pcss.pl/openagri/openagri-smartirrigationcontroller) - Models water demand and soil-moisture dynamics for crop-specific irrigation scheduling.
- [Compost Reasoning Engine](https://github.com/fedjo/monicompost) - Analyses temperature, moisture, and oxygen data to recommend compost-management actions.
- [AgriVision](https://github.com/GEvang/agrivision-pipeline) - Computer-vision pipeline for agricultural imagery, with associated Co-AgriADS hardware and data documentation.
- AgriTwin - Prototype digital-twin platform for agricultural monitoring, data visualisation, reporting, and decision support.
- Spotify - AI-powered system for real-time detection and prediction of olive fruit fly and olive moth risks.
- [iAgro](https://github.com/Agrobitsrl/PDM-fuzzymodel) - Forecasts crop pest and disease pressure under changing environmental conditions.
- [Pre-Configured Reporting Templates for PGI/DPO](https://github.com/Agrobitsrl/reporting-templates) - Converts JSON-based inputs into formatted compliance, sustainability, and operational reports.
- [SheepCare](https://github.com/itdepartment-cnta/Sheepcare.git) - Collects, monitors, and analyses flock health, welfare, and production data.
- [SFS SmartFeed Backend](https://github.com/inokron-doo/OA-Cloud-Backend) - Centralised service for feed-monitoring data, IoT telemetry, predictive analytics, and alerts.
- [SFS LoRa Concentrator Node Firmware](https://github.com/inokron-doo/OA-Concentrator) - Gateway firmware that aggregates sensor telemetry and forwards it to SmartFeed services.
- [SFS SmartFeed Edge Processing Software](https://github.com/inokron-doo/OA-LocalNodeREDsetup) - Collects and processes on-farm feed and environmental data, with local storage and cloud synchronisation.
- [SFS SmartFeed Web App](https://github.com/inokron-doo/OA-Cloud-Frontend) - React, TypeScript, and Vite dashboard for SmartFeed monitoring and analytics.
- [SFS LoRa Sensor Node Firmware](https://github.com/inokron-doo/OA-Sensor) - Monitors feed levels, temperature, and humidity for LoRa-enabled livestock feeding systems.
- SCIBee Beehive Data Aggregator - Aggregates and organises hive and environmental sensor data across the SCIBee platform.
- SCIBee Beehive Data Evaluator - Analyses beehive monitoring data to assess colony performance, health, and environmental impacts.
- SCIBee Community Data Hub - Integrates sensor networks, telemetry, and analytics for real-time colony-health assessment.

## Data Models & APIs

No tools are currently listed in this category.

## Datasets & AI Models

- [OpenAgri Vineyard Image Dataset](https://zenodo.org/records/19698544) - Annotated vineyard imagery for yield estimation, disease detection, and canopy analysis.
- [Pre-final AI models for yield estimation, disease detection, and vigour estimation](https://zenodo.org/records/19698544) - YOLO-based vineyard models for grape-cluster detection, disease symptoms, and canopy-vigour assessment.
- [Annual Composting Cycle](https://zenodo.org/records/18984012) - Time-series sensor measurements from two compost piles during fermentation.
- Canopy Biometrics Model - Processes 3D point clouds to estimate canopy geometry and derive variable-rate spraying recommendations.
- [Frost Injury Alert Model](https://github.com/Agrobitsrl/FD-freezinginjury) - Evaluates crop vulnerability by growth stage and temperature to provide freezing-injury alerts.
- [SCC classification](https://github.com/itdepartment-cnta/Sheepcare.git) - Machine-learning module for sheep-monitoring data and automated livestock-management decisions.

## Hardware & IoT Specs

- [UHF RFID smart case](https://github.com/e-peltier18/Animal-visit-reporting/tree/main) - RFID reader system for automated animal identification and visit tracking.
- [Custom 3D printed enclosure - Drone-Mounted Edge Computing Enclosure](https://github.com/ilvo-openagri) - 3D-printed UAV enclosure for edge-computing and sensing components.
- [SFS LoRa Sensor Network Node](https://github.com/inokron-doo/OA-HWcomponents) - Dual-role LoRa node for feed-level and microclimate monitoring.
- SCIBee Beehive Base Controller - Embedded controller for sensor management, telemetry collection, and device communication.
- SCIBee Beehive Base Structure - Smart beehive framework for integrating monitoring sensors and IoT equipment.
- SCIBee Beehive Entrance Counter - Automated system for measuring hive ingress and egress activity.
- SCIBee Visual Varroa Detector - Vision-based hardware platform for Varroa-mite detection and hive-health assessment.

## Documentation

- [Edge based smart irrigation system architecture](https://ligit.pit.lukasiewicz.gov.pl/openagri) - Edge-computing architecture for sensor-driven irrigation monitoring, control, and water-use efficiency.
- [MOSIC – Modular Open-Source Irrigation Controller](https://github.com/altsol/mosic) - Modular irrigation-management solution for monitoring and controlling precision-irrigation systems.
- [Somatic Cell Count](https://doi.org/10.5281/zenodo.22748856) - Data resource of somatic-cell-count records and metadata for dairy health and mastitis monitoring.
- [Estrus detection](https://doi.org/10.5281/zenodo.22748342) - Data resource of estrus observations and metadata for reproductive-status classification.
- SCIBee Varroa Mite Images - Annotated bee images with and without Varroa mites for AI detection and colony-health monitoring.

## Standards & Interoperability

No tools are currently listed in this category.

## Contributing

Contributions, fixes, and additions are welcome! Please read the [Contributing Guidelines](CONTRIBUTING.md) before submitting a pull request.
