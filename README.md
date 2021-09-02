# Prandtl-Finite-Wing-Formulation  
Numerical solution using prandtl's lifting line theory is provided for Elliptical wing, Rectangular wing, Tapered Wing of taper ratio of 2:1 as well as 3:1  
Bound Circulation is calculated in each case using Fourier series and plotted against the span   
Incase of Elliptical wing the numerical soltion is compared with the theoritical solution (analytical solution)  
Rectagular wing and tapered wings are solved for two cases, when the wing is divided into 40 segments and when divided into 20 segments  
  
# Inferences
1. Since the lift coefficient depends on first fourier coefficient (A1) alone, the lift is highest for rectangular wing and least for 3:1 tapered wing.  
2. By comparing the values of induced drag coefficient in terms of fourier coefficients it can be concluded that - Tapered wings have lower induced drag compared to rectagular wing.   
3. It can be observed that the bound circulation values at each point decreases as we increase the taper ratio.  
4. Evidently, we can see that the graphs coresponding to tapered wings in case of 40 segments, are overfitting. Hence the results/plots obtained in that case makes less sense.  
5. However, by decreasing the number of segments to 20 we have this problem is solved and the plots obtained make much more sense to draw conclusions.  
