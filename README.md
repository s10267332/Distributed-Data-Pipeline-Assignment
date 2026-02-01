# Real-Time Bus Arrival Monitoring System

## Project Overview

This project builds a real-time transport monitoring system using Singapore LTA DataMall APIs to help students and parents make safer commuting decisions. It focuses on bus stop **01121**, located outside a primary school, where uncertainty in bus arrival times often causes stress, long waiting periods, and missed buses.

The system retrieves live bus arrival data, bus stop metadata, and MRT service alerts, then transforms messy JSON responses into a clean, human-friendly dataset using Alteryx. The final output is visualized through an interactive SAP Analytics Cloud dashboard designed to be simple enough for children while still informative for adults.

The goal is to create a reliable, distraction-free alternative to ad-heavy transport apps and provide a clearer commuting experience.

---

## Key Features

- Real-time bus arrival tracking using LTA DataMall API
- Integration of bus stop metadata and MRT service alerts
- Automated JSON parsing and transformation pipeline in Alteryx
- Conversion of technical abbreviations into readable labels
- Smart handling of missing values using “Not Applicable”
- Arrival time conversion into human-friendly countdowns
- Accessibility indicators (Wheelchair Accessible buses)
- Crowd level interpretation (Seats Available / Standing / Limited Standing)
- SAP Analytics Cloud dashboard for interactive visualization

---

## Workflow Highlights

- API integration with secure headers and authentication
- JSON flattening using JSON Parse + Cross Tab tools
- Multi-field transformation for efficiency
- Data cleansing and validation pipeline
- Join operations to enrich live data with context
- Automated formatting for end-user readability

---

## Insights

- Double decker buses appear more frequently during off-peak periods
- Accessibility coverage at the stop is consistently high
- Crowd load indicators reveal passenger demand patterns
- MRT disruption alerts provide broader transport awareness
- Missing API values handled safely to avoid broken dashboards

---
