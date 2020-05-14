# vkThesis
This repository contains both Mathematica files used and audio files generated during my senior thesis project and serves as a companion to the thesis. 

Mathematica Files: 

Build-A-Bell-Workshop.nb can be used to generate the \nabla^4 eigenmodes, eigenfrequencies and coupling coefficients (H and E) of arbitrary rectilinear shapes with "simply-supported" boundary conditions. 

midpointRungeKutta.nb can be used to solve the von Karman equations for a given plate, and it requires the output files of Build-A-Bell-Workshop.nb. 

HeatMatrix.nb generates heat matrices (as seen in Chapter 3) that represent the transverse mode mixing (faciliated by the in-plane modes) for a given plate (this also requires the output files of Build-A-Bell-Workshop.nb as it is using a simplified version of midpointRungeKutta.nb). 
