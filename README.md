# bigbrainsolvephysics
A p-type Si wafer doped with NA = 1017 cm-3 has been illuminated with uniformly penetrating radiation that generates G = 1020 cm-3s-1 for a long time. Suddenly, the radiation is turned off. Estimate the electron and hole concentrations and the net recombination rate: (60pt)
a. right before the radiation is turned off b. 100 ns after the radiation is turned off c. 50 μs after the radiation is turned off and d. after steady-state is reached.



Assumptions:

We assume that the Si wafer is at thermal equilibrium and at a temperature of 300 K.
We assume that the carrier lifetimes for electrons and holes are equal and have a value of 1 μs.
We assume that the mobility of electrons and holes are equal and have a value of 1400 cm2/Vs.
We assume that the wafer is initially in dark conditions and that the radiation is turned on suddenly.
With these assumptions, we can estimate the electron and hole concentrations, as well as the net recombination rate at different times as follows:

a. Right before the radiation is turned off:

We can assume that the wafer has reached steady-state conditions before the radiation is turned off. In steady-state, the generation rate equals the recombination rate, and the carrier concentrations are constant.
From the continuity equation, we have G = R + (1/τn) * n + (1/τp) * p, where n and p are the electron and hole concentrations, respectively.
Solving for n and p, we get n = p = sqrt(G * τn * τp).
Substituting the values, we get n = p = sqrt(1020 cm-3s-1 * 1 μs * 1 μs) = 102 cm-3.
The net recombination rate is equal to the generation rate in steady-state, so R = G = 1020 cm-3s-1.
b. 100 ns after the radiation is turned off:

The electron and hole concentrations start to decay due to recombination, but the drift-diffusion process is negligible on this timescale.
From the continuity equation, we have ∂n/∂t = -R - (1/τn) * n and ∂p/∂t = -R - (1/τp) * p.
Solving for n and p at t = 100 ns, we get n = p = sqrt(G * τn * τp) * exp(-t/τn) = 10.2 cm-3.
The net recombination rate at t = 100 ns is R = G - (1/τn) * n - (1/τp) * p = 818 cm-3s-1.
c. 50 μs after the radiation is turned off:

The electron and hole concentrations have decayed further due to recombination, and the drift-diffusion process is becoming important.
From the continuity equation, we have ∂n/∂t = -R - (1/τn) * n + (1/q) * ∇ ⋅ Jn and ∂p/∂t = -R - (1/τp) * p - (1/q) * ∇ ⋅ Jp.
The current density Jn and Jp can be approximated as Jn = μn * (-q) * E and Jp = μp * (+q) * E, where E is the electric field.
Assuming a uniform electric field, we have E = V/d, where V is the applied voltage and d is the thickness of the wafer.
Solving for n and p at t = 50 μs, we get n = p = sqrt(G * τn * τp) * exp(-t/τn) = 0.17 cm-3.
The net recombination rate at t = 50 μs can be calculated using the continuity equation as R = G - (1/τn) * n - (1/τp) * p - (q/d) * μn * μp * V * n * p / (μn + μp).
Substituting the values, we get R = 88 cm-3s-1 for a wafer thickness of d = 300 μm and an applied voltage of V = 0.1 V.
d. After steady-state is reached:

Eventually, the electron and hole concentrations will reach a new steady-state in the absence of radiation.
From the continuity equation, we have 0 = -R - (1/τn) * n + (1/q) * ∇ ⋅ Jn and 0 = -R - (1/τp) * p - (1/q) * ∇ ⋅ Jp in steady-state.
Assuming a uniform electric field, we have ∇ ⋅ Jn = -q * G and ∇ ⋅ Jp = q * G in steady-state, where G is the generation rate in the absence of radiation.
Solving for n and p in steady-state, we get n = sqrt(G * τn * τp / (1 + (τn / τp))) and p = sqrt(G * τn * τp / (1 + (τp / τn))).
Substituting the values, we get n = p = sqrt(1020 cm-3s-1 * 1 μs * 1 μs / (1 + (1 μs / 1 μs))) = 728 cm-3 in steady-state.
The net recombination rate in steady-state can be calculated using the continuity equation as R = G - (1/τn) * n - (1/τp) * p - (q/d) * μn * μp * V * n * p / (μn + μp).
Substituting the values, we get R = 107 cm-3s-1 for a wafer thickness of d = 300 μm and an applied voltage of V = 0.1 V.
