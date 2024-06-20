# WQModeling_Examples
## Author: Salma M. Elsherif
## Last Update: June 2024

### Different examples of Water Quality (WQ) Modeling are provided herein:
- **PDEOnePipe.xlsm**: This file is an Excel Macro-Enabled Workbook that models chlorine evolution in a simple single pipe connected by two nodes with known initial chlorine concentrations. The upstream node is assumed to have a fixed concentration, while the downstream node, having no other connected pipes, has a concentration equal to the last pipe's segment concentration. The WQ dynamics are modeled using advection-reaction partial differential equations (PDEs) discretized with the Upwind scheme. Additionally, the reaction dynamics are based on a single-species reaction model.
