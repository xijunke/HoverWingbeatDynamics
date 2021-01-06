# The numerical solution for flapping wing hovering wingbeat dynamics

by Xijun Ke, Weiping Zhang, Jinhao Shi and Weidong Chen，Aerospace Science and Technology

https://www.sciencedirect.com/science/article/abs/pii/S1270963820311561

https://doi.org/10.1016/j.ast.2020.106474



**Abstract**: *The production of wingbeat motion of flapping wing hovering flight are determined by the actuating, aerodynamic and inertia forces/moments, which influence the dynamic unsteadiness and controllability of flapping wing flying. This paper presents the feasible solution for cracking the problem of two degrees of freedom (two DoFs, namely, flapping and pitch motion, respectively) highly coupled nonlinear hovering wingbeat dynamics. Firstly, two DoFs nonlinear hovering wingbeat dynamic ordinary differential equations (ODEs) are derived on basis of the extended quasi-steady aerodynamic and inertial forces/moments model. Then, we perform their numerical solution by using tractable ODEs numerical algorithm, boundary value problem-solving format, and least square method. The numerical results have a good consistency with those measured by Dr. Muijres. Moreover, the adjustable rule of phase offset of wing pitch angle relative to the flapping angle is quantificationally studied by introducing frequency ratio between pitch frequency and flapping frequency. We find that the phase offset can be directly regulated by wing pitch hinge stiffness or indirectly modulated by frequency ratio, and the peak value of wing pitch angle monotonously decreases with the increase of wing pitch hinge stiffness, opposite to the angle of attack (AoA). This adjustable rule paves a useful way for the bio-inspired flapping wing micro aerial vehicle (FWMAV) featuring passive or semi-passive pitch flexible hinge to maintain high variable AoA.*



![Fig1_Left_wing_body_model](https://github.com/xijunke/FWMAV_HoverWingbeatDynamics/blob/main/pic_png/Fig1_Left_wing_body_model_s1_4_12_2.png)

![Fig1_Right_wing_body_model](https://github.com/xijunke/FWMAV_HoverWingbeatDynamics/blob/main/pic_png/Fig1_Right_wing_body_model_s1_4_13_2.png)

***Figure 1: Coordinate systems and denition of right-wing Euler angles relative to the stroke plane in right wing root frame (xrryrrzrr) [9, 10].***


![The numerical solving procedure](https://github.com/xijunke/FWMAV_HoverWingbeatDynamics/blob/main/pic_png/Fig2.png)

***Figure 2: The numerical solving procedure of two coupled wingbeat dynamic nonlinear ODEs (WGP is the abbreviation of wing geometry parameters).***


![3D sandwich geometry model of the compliant hinge](https://github.com/xijunke/FWMAV_HoverWingbeatDynamics/blob/main/pic_png/Fig3.png)

***Figure 3: 3D sandwich geometry model of the compliant hinge(a rigid layer: gray; exible layer: yellow).***


![The comparison of the simulated results acquired by the decoupled strategy with the experimental ones](https://github.com/xijunke/FWMAV_HoverWingbeatDynamics/blob/main/pic_png/Fig4.png)

***Figure 4: The comparison of the simulated results with the experimental ones: (a) Given the measured apping angle as an input (black solid line), the simulated pitch angle (blue
dot-dash line) and the measured pitch angle (red solid line); (b) The phase diagram for \dpsi_{sim}(t) and  \psi_{sim}(t). (c) Given the measured pitch angle as one of the inputs (black solid
line), the simulated apping angle (blue dot-dash line) and the measured apping angle (red solid line). (d) The phase diagram for \dphi_{sim}(t) and \phi_{sim}(t).***


![The comparison of simulated results acquired by the coupled strategy with experimental ones](https://github.com/xijunke/FWMAV_HoverWingbeatDynamics/blob/main/pic_png/Fig5.png)

***Figure 5: The comparison of simulated results acquired by the coupled strategy with experimental ones: (a) the simulated apping and pitch angle are shown in red and blue solid lines, respectively, while those measured are plotted in red and blue dot-dash lines,respectively; (b) The phase plot for \dpsi_{sim}(t) and \psi_{sim}(t); (c) The phase plot for \dphi_{sim}(t) and \phi_{sim}(t).***


![The peak value of simulated pitch angle changes with pitch hinge stiffness](https://github.com/xijunke/FWMAV_HoverWingbeatDynamics/blob/main/pic_png/Fig6.png)

***Figure 6: (a) The peak value of simulated pitch angle (\psi_{sim;peak}) changes with pitch hinge stiffness (k_{pitch;hinge}). (b) The phase offset (\delta) varies with frequency ratio (\lamda).***


![The phase offset of the simulated pitch angle relative to the experimentally measured pitch angle](https://github.com/xijunke/FWMAV_HoverWingbeatDynamics/blob/main/pic_png/Fig7.png)

***Figure 7: The phase offset of the simulated pitch angle (blue line for the delayed phase,cyan line for the advanced phase and green dot-dash line for the symmetry phase) relative to the experimentally measured pitch angle (red solid line). The abscissa axis is normalized by the apping period.***



