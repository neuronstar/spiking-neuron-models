Single Neuron Models
===================
Hudgkin-Huxley Model
-------------
Biological principles: ion channel oppeness
$$
I(t)= I_\mathrm{cap}(t)+\sum_{k}I_k(t)
$$
This equation summarize the current run over the all ion channles. Three types of ion channles are considered: sodium channels, potassium channels, and unspecific leaky channels.
$$
C\frac{du}{dt}=-\sum_kI_k(t)+I(t)
$$
$C\frac{du}{dt}$ denotes the current across the capacitor.
$$
\sum_kI_k(t) = g_{Na}m^3h(u-E_{Na})+g_kn^4(u-E_k)+g_L(u-E_L)
$$
This equation denotes the ionic channel currency, where m , n, and h could be analyzed with master equation.
$$
\dot m= \alpha_m(u)(1-m)-\beta_m(u)m
$$
$$
\dot n= \alpha_n(u)(1-n)-\beta_n(u)n
$$
$$
\dot h= \alpha_h(u)(1-h)-\beta_h(u)h
$$
Advantages: represent real biological process
Disadvantage: computation-expensive

2D Model
-------------


Leaky Integrate-and-Fire Model
-------------
$$
I(t)=\frac{u(t)}{R}+C\frac{du}{dt}
$$
where $\tau_m=RC$ is the *leaky integrator*,
so it yields thisequation:
$$
\tau_m\frac{du}{dt}=-u(t)+RI(t)
$$

Nonlinear Integrate-and-Fire Model
-------------

Spike Response Model 
-------------
no equations available

Izhikevich Model
-------------



