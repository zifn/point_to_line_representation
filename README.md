# point_to_line_representation

## Motivation
Any individual function can be represented in several different ways. The common way that these functions are visualized is as a collection of points where for every $x$ value a corresponding $y$ value is calculated and plotted where the tuples take the form $(x, y(x))$. However, this function can be represented as function of it's derivative using the Legendre transform. This new function ($\psi(P)$), takes as input the slope of a line and computes the y intercept of the line that will make that line tangent to the original function $y(x)$.  The existence of $\psi(P)$ allows functions to be visualized not as a collection of points but as a collection of lines tangent to the curve being represented. This has the effect of transforming the curve from a point geometric to a line geometric representation. This python script computes and plots this collection of tangent curves and compares it to the point geometric representation

This method of taking a function and looking at it's Legendre transform has been a valuable technique in physics. It acts as the glue between Lagrangian and Hamiltonian mechanics, and it's the link between the various representations of the equation of state in thermodynamics (ie. Energy $E$ and Enthalpy $H$ ).

## Sample Output

![Alt text](sample/xlnx_point.png?raw=true "xln(x) point representation")

![Alt text](sample/xlnx_line.png?raw=true "xln(x) line representation")

![Alt text](sample/xlnx_point_and_line.png?raw=true "xln(x) point and line representation")
