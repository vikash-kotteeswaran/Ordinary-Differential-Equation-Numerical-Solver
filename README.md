# Ordinary-Differential-Equation-Numerical-Solver
Solving Ordinary Differential Equation Numerically using 4th Order Runge-Kutta Method and can also be used to perform Integrations Numerically
### Recommendations:
* The preference would be to take independent variable x or t as x1, dependent variable y as x2 and so on.
* Solving higher order differential equations (Order>1) requires decomposition of higher order differential equations into several first order differential equations.
* Provide Initial conditions to begin the calculation.
### Example:
![](https://latex.codecogs.com/gif.latex?\frac{d^2y}{dx^2}&plus;\frac{dy}{dx}=x)
<br />
<br /> This can be broken down into First order differential equations 
<br />
<br />![](https://latex.codecogs.com/gif.latex?\frac{dy}{dx}=z)
<br />![](https://latex.codecogs.com/gif.latex?\frac{dz}{dx}=x-z)
