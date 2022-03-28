# IGPQBio_workshop
PySB workshop for Vanderbilt University, IGP Quantitative Biology course

This example demonstrates how one can implement and simulate a system model using PySB. In this example, a simple model of Covid-19 spread is simulated. This model can be simulated by solving a system of first order ODEs given by: dy/dt = f(y, t). However, using PySB, the system can be given as a set of reaction rules and the underlying ODE system is solved at runtime. This representation is typically clearer and easier to update and maintain.

## Launch
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mustafaozen/IGPQBio_workshop/main?labpath=Workshop1_CovidSpread.ipynb)

## Credits
This example was adapted from a previously implemented PySB tutorial by Alex Lubbock.
