# Active Learning for Selecting Sensor Locations During Processing of Composite-Tool Systems

The model performs sensor selection in composites processing. It particullary provides the best **location** to put the limited number of sensors and limited available area. We have uncertainties in:
1. number of available sensors
2. uncertainty in measurements of sensors
3. available area to put the sensors
4. all material properties  (18 material parameters)
5. air temperature inside the autoclave
6. initial temperature of the composite and tool (uncertainty in the room temperature)

We are prediction the **best** location(s) to put the sensors.
<br>
<p align="center">
<img  align="center" src="https://github.com/saniaki/active_learning/blob/main/images/image01.jpg" width="700"/>  
<br>
<br>
<br>
For stochastic modelling of the processing, the proposed bootstrap filtering model is sued: \
https://github.com/saniaki/stochastic_modelling

The solver for generating data is a FEM model on thermochemical heat processing: \
https://github.com/saniaki/FEM-heat

For optimization, Scikit-Optimize, a sequential model-based optimization library in Python is used: \
https://scikit-optimize.github.io/stable/ \
https://scikit-optimize.github.io/stable/auto_examples/bayesian-optimization.html \
https://scikit-optimize.github.io/stable/modules/generated/skopt.gp_minimize.html#skopt-gp-minimize


**Acknowledgement** <br>
This model is developed with support of <br>
<br>
<p align="center">
<img  align="center" src="https://github.com/saniaki/active_learning/blob/main/images/image02.png" width="550"/> 
