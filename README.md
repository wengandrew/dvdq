# Differential Voltage Analysis

Differential voltage (dV/dQ) analysis code.

https://www.frontiersin.org/articles/10.3389/fenrg.2023.1087269/full

## Overview

The code in this repository consists of two parts:

### 1. Voltage fitting method tools

Code to convert full cell C/20 voltage curves into electrode level metrics such as cathode capacity ($Q_p$), anode capacity ($Q_n$), lithium inventory ($Q_{Li}$), etc.

Start in `src-matlab/process_voltage_curves...`

### 2. Data visualization library

Code to visualize the outputs from the dV/dQ methods and to prepare the figures presended in the Frontiers paper.

Start in `notebooks/...`

## Getting Started

To get started with the voltage fitting method tools, start in `src-matlab/process_voltage_curves...`. In order for the scripts to run, you will first need to import the raw datasets which contain the C/20 voltage curves. Go to `data/` for more instructions.

To get started with the data visualization, set up your Python environment according to `notebooks/README.md`
