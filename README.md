# muelless_diffusion2d

This Python package solves the 2D heat diffusion equiation and plots the result.

## Description
This code solves the diffusion equation over a two dimensional square domain which is at a certain temperature, and a circular disc at its center which is at a higher temperature. The diffusion equation is solved using the finite-difference method. The thermal diffusivity and initial conditions of the system can be changed by the user. The code produces four plots at various timepoints of the simulation. The diffusion process can be clearly observed in these plots.

## Installing the package
```
python -m pip install --index-url https://test.pypi.org/simple/ -- extra-index-url https://pypi.org/simple/muelless_diffusion2d
```

## Running this package
```
from muelless_diffusion2d import solves

solve()

solve(dx=0.1, dy=0.1, D=4)
```

## Citing
Tutorial of Simulation Software Engineering at University of Stuttgart by [Ishaan Desai](https://github.com/IshaanDesai)
