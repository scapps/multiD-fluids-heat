# ChBE 3300: Multidimensional Fluids and Heat Transport

## Course Description

This repository contains Jupyter notebooks and computational resources for teaching 2-D and 3-D fluid dynamics and heat transfer in Chemical Engineering.

## Repository Structure

```
.
├── notebooks/
│   ├── 01-introduction/          # Python basics and numerical methods review
│   ├── 02-1D-problems/            # 1-D steady and transient problems
│   ├── 03-2D-fluids/              # 2-D fluid flow problems
│   ├── 04-2D-heat-transfer/       # 2-D heat conduction and convection
│   ├── 05-3D-fluids/              # 3-D fluid flow problems
│   ├── 06-3D-heat-transfer/       # 3-D heat transfer problems
│   └── 07-advanced-topics/        # Coupled problems and advanced methods
├── data/                          # Data files for examples
├── figures/                       # Generated figures and visualizations
├── requirements.txt               # Python dependencies
└── README.md                      # This file
```

## Getting Started

### Prerequisites

- Python 3.8 or higher
- pip package manager

### Installation

1. Clone this repository:
   ```bash
   git clone <repository-url>
   cd multiD-fluids-heat
   ```

2. Create a virtual environment (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

4. Launch Jupyter:
   ```bash
   jupyter lab
   ```

## Topics Covered

### 1. Introduction
- Python and NumPy fundamentals
- Numerical methods review
- Finite difference methods

### 2. 1-D Problems
- Steady-state heat conduction
- Transient heat transfer
- Pipe flow

### 3. 2-D Fluid Flow
- Lid-driven cavity flow
- Channel flow
- Stream functions and velocity potentials
- Navier-Stokes equations

### 4. 2-D Heat Transfer
- Steady-state conduction in 2-D
- Convection-diffusion problems
- Boundary conditions

### 5. 3-D Fluid Flow
- 3-D flow visualization
- Complex geometries
- Pressure-velocity coupling

### 6. 3-D Heat Transfer
- 3-D conduction problems
- Coupled heat and mass transfer
- Industrial applications

### 7. Advanced Topics
- Coupled fluid flow and heat transfer
- Turbulence modeling basics
- Computational efficiency

## Usage

Navigate to the `notebooks/` directory and open the desired topic folder. Notebooks are numbered in recommended order.

## Contributing

If you find errors or have suggestions for improvements, please open an issue or submit a pull request.

## License

This material is intended for educational purposes for ChBE 3300 students.

## Contact

For questions about the course material, please contact your instructor.
