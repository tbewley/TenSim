# TenSim
Tensegrity Simulator - code for computing the statics and dynamics of tensegrity systems
All codes in simple (easy to extend) Matlab syntax.

Implements the equations of static equilibrium of a tensegrity system as Ax=u. Tensions via an LP. Plots.

The two main codes (TenSimStatics.m and TenSimDynamics.m) implement the equations in sections 3.1 and 3.2 of:
*Bewley (2019) Stabilization of low-altitude balloon systems, Part 2: riggings with multiple taut ground tethers, analyzed as tensegrity systems*.

The plotting code (tensegrity_plot.m) makes some rudimentary 2D or 3D plots, as appropriate.
All figures from the above paper are included as examples, in addition to a few from Skelton and de Oliveira (2009) Tensegrity Systems. Please do submit pull requests as you implement more examples! :)
