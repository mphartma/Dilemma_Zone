# Dilemma Zone Analysis

This project analyzes driver decision-making at a signalized intersection during the onset of a yellow light, with a focus on the "dilemma zone": the region where a driver may be unable to either stop comfortably before the intersection or proceed through it safely. The model uses vehicle speed, distance from the stop line, reaction assumptions, and braking behavior to classify likely outcomes and visualize the conditions that produce safe or unsafe decisions.

The goal of the project is to study how intersection approach conditions influence driver response and to identify the boundary between stopping and proceeding. This kind of analysis is relevant to traffic engineering, roadway safety, and signal timing design.

## Project Contents

- `dilemma_zone_analysis.ipynb` — main notebook containing the model, calculations, plots, and discussion

## Methods

The analysis models vehicle motion near an intersection at the moment a signal changes from green to yellow. Using kinematic equations and decision criteria, the code evaluates whether a driver can:

- stop before the intersection under reasonable braking,
- clear the intersection before the signal phase changes,
- or enter the dilemma zone, where neither option is clearly safe.

The notebook explores how changing parameters such as speed and position affects the outcome and visualizes the resulting decision regions.

## Results

The project produces plots that illustrate:

- stopping and clearing boundaries,
- regions corresponding to safe stop and safe go decisions,
- the parameter space associated with the dilemma zone.

These results help show how a vehicle’s approach speed and distance from the intersection determine whether a conflict region appears.

## How to Run

1. Clone this repository.
2. Open `dilemma_zone_analysis.ipynb` in Jupyter Notebook or JupyterLab.
3. Run all cells in order.
4. View the generated plots and analysis in the notebook.

## Tools Used

- Python
- NumPy
- Matplotlib
- Jupyter Notebook

## Notes

This repository is a cleaned and public-facing version of an academic project. Course-specific files, grading materials, and assignment instructions have been removed so the repository focuses on the project itself and its technical content.