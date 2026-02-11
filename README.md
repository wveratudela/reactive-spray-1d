# Reactive 1D Spray Column with Chemical Kinetics

## Overview

This project implements a custom 1D reactive spray column model coupling droplet evaporation with gas-phase chemical kinetics using Cantera.

The model solves coupled mass, species, and energy balances along a one-dimensional domain to study evaporation–reaction interactions and thermal behavior.

This is an original implementation intended as a minimal, transparent research model.

---

## Model Components

- 1D finite-difference spatial discretization  
- Droplet evaporation source terms  
- Gas-phase chemical kinetics via Cantera  
- Energy balance  
- Modular Python implementation  

---

## Structure

reactive-spray-1d/
├── src/
│   ├── solver.py        # Main time integration loop
│   ├── spray.py         # Spray evaporation model
│   └── kinetics.py      # Cantera kinetics interface
├── notebooks/           # Exploration and visualization
├── results/             # Output figures and data

---

## Goals

- Study coupling between evaporation and chemical reactions  
- Explore temperature and species profiles along the column  
- Provide a clean reference implementation for reactive spray modeling  

---

## Current Status

Skeleton implementation in place.  
Physics and numerics will be added incrementally.

---

## Planned Features

- Evaporation model
- Species transport
- Energy equation
- Cantera integration
- Visualization of temperature and species profiles

---

## What I Learned (ongoing)

- Coupling stiff chemical kinetics with transport equations
- Numerical stability considerations in reactive systems
- Modular design for scientific Python projects

---

## Notes

This model is fully original work. Parameters and physics are simplified for public demonstration purposes.
