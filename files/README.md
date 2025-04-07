---
jupyter:
  jupytext:
    text_representation:
      extension: .md
      format_name: markdown
      format_version: '1.3'
      jupytext_version: 1.13.8
  kernelspec:
    display_name: Python 3 (ipykernel)
    language: python
    name: python3
---

# Tutorials for QuTiP Version 5

## Contents

  - [Example notebooks](#Example-notebooks)
    - [Python Introduction](#Python-Introduction)
    - [Visualization](#Visualization)
    - [Quantum information processing](#Quantum-information-processing)
      - [Quantum circuits and algorithms](#Quantum-circuits-and-algorithms)
      - [Pulse-level circuit simulation](#Pulse-level-circuit-simulation)
    - [Time evolution](#Time-evolution)
    - [Hierarchical Equations of Motion](#Hierarchical-Equations-of-Motion)
    - [Miscellaneous tutorials](#Miscellaneous-tutorials)
  - [Quantum mechanics lectures with QuTiP](#Quantum-mechanics-lectures-with-QuTiP)
  - [Contributing](#Contributing)


## Example notebooks

### Python Introduction


  - [Introduction to Python](./tutorials/python-introduction/001_Beginning_Python.ipynb)

  - [Introduction to NumPy Arrays](./tutorials/python-introduction/002_NumPy_Array_Basics.ipynb)

  - [Plotting in Python Using Matplotlib](./tutorials/python-introduction/003_Matplotlib_Plotting.ipynb)

  - [Lecture 0 - Introduction to QuTiP](./tutorials/python-introduction/004_link_to_lecture_0.ipynb)



### Visualization


  - [Animation demos](./tutorials/visualization/animation-demo.ipynb)

  - [Bloch Sphere animation](./tutorials/visualization/bloch-sphere-animation.ipynb)

  - [Bloch Sphere with colorbar](./tutorials/visualization/bloch_sphere_with_colorbar.ipynb)

  - [Energy-level diagrams](./tutorials/visualization/energy-levels.ipynb)

  - [Pseudo-probability functions](./tutorials/visualization/pseudo-probability-functions.ipynb)

  - [Quantum Process Tomography](./tutorials/visualization/quantum-process-tomography.ipynb)

  - [Qubism visualizations](./tutorials/visualization/qubism-and-schmidt-plots.ipynb)

  - [Using qutip.distributions](./tutorials/visualization/distributions.ipynb)

  - [Visualization demos](./tutorials/visualization/visualization-exposition.ipynb)

  - [Wigner functions](./tutorials/visualization/JC-model-wigner-function.ipynb)



### Quantum information processing

This section requires an additional package [qutip-qip](https://github.com/qutip/qutip-qip),
which is already installed in the try-qutip environment.

#### Quantum circuits and algorithms


  - [Decomposition of the Toffoli gate in terms of CNOT and single-qubit rotations](./tutorials/quantum-circuits/qip-toffoli-cnot.ipynb)

  - [Imports and Exports QASM circuit](./tutorials/quantum-circuits/qasm.ipynb)

  - [Plotting and Customizing Quantum Circuits using MatRenderer](./tutorials/quantum-circuits/matrenderer-plot.ipynb)

  - [Plotting and Customizing Quantum Circuits using TextRenderer](./tutorials/quantum-circuits/textrenderer-plot.ipynb)

  - [QuTiP example: Quantum Gates and their usage](./tutorials/quantum-circuits/quantum-gates.ipynb)

  - [Quantum Teleportation Circuit](./tutorials/quantum-circuits/teleportation.ipynb)


#### Pulse-level circuit simulation


  - [Compiling and simulating a 10-qubit Quantum Fourier Transform (QFT) algorithm](./tutorials/pulse-level-circuit-simulation/qip-10-qubit-QFT-algorithm.ipynb)

  - [Custimize the pulse-level simulation](./tutorials/pulse-level-circuit-simulation/qip-customize-device.ipynb)

  - [Examples for OptPulseProcessor](./tutorials/pulse-level-circuit-simulation/qip-optpulseprocessor.ipynb)

  - [Scheduler for quantum gates and instructions](./tutorials/pulse-level-circuit-simulation/qip-scheduler.ipynb)

  - [Simulating randomized benchmarking](./tutorials/pulse-level-circuit-simulation/qip-randomized-benchmarking.ipynb)

  - [Simulating the Deutsch–Jozsa algorithm at the pulse level](./tutorials/pulse-level-circuit-simulation/qip-processor-DJ-algorithm.ipynb)

  - [measuring the relaxation time with the idling gate](./tutorials/pulse-level-circuit-simulation/qip-relaxation-measurement-with-the-idling-gate.ipynb)



### Time evolution


  - [<code>QobjEvo</code>: time-dependent quantum objects](./tutorials/time-evolution/001_qobjevo.ipynb)

  - [Schrödinger Equation Solver: Larmor precession](./tutorials/time-evolution/002_larmor-precession.ipynb)

  - [Master Equation Solver: Single-Qubit Dynamics](./tutorials/time-evolution/003_qubit-dynamics.ipynb)

  - [Master Equation Solver: Vacuum Rabi oscillations](./tutorials/time-evolution/004_rabi-oscillations.ipynb)

  - [Master Equation Solver: Dynamics of a Spin Chain](./tutorials/time-evolution/005_spin-chain.ipynb)

  - [Monte Carlo Solver: Birth and Death of Photons in a Cavity](./tutorials/time-evolution/006_photon_birth_death.ipynb)

  - [Bloch-Redfield Solver: Two Level System](./tutorials/time-evolution/007_brmesolve_tls.ipynb)

  - [Bloch-Redfield Solver: Time dependent operators](./tutorials/time-evolution/008_brmesolve_time_dependence.ipynb)

  - [Bloch-Redfield Solver: Dissipative Atom-Cavity system](./tutorials/time-evolution/009_brmesolve-cavity-QED.ipynb)

  - [Bloch-Redfield Solver: Phonon-assisted initialization](./tutorials/time-evolution/010_brmesolve_phonon_interaction.ipynb)

  - [Floquet Solvers](./tutorials/time-evolution/011_floquet_solver.ipynb)

  - [Floquet Formalism](./tutorials/time-evolution/012_floquet_formalism.ipynb)

  - [Non-Markovian Monte Carlo Solver: Two Physical Examples](./tutorials/time-evolution/013_nonmarkovian_monte_carlo.ipynb)

  - [Stochastic Solver: Heterodyne Detection](./tutorials/time-evolution/015_smesolve-heterodyne.ipynb)

  - [Stochastic Solver: Mixing stochastic and deterministic equations](./tutorials/time-evolution/016_smesolve-inefficient-detection.ipynb)

  - [Stochastic Solver: Photo-current detection in a JC model](./tutorials/time-evolution/017_smesolve-jc-photocurrent.ipynb)

  - [Stochastic vs. Monte-Carlo Solver: Cat states become coherent](./tutorials/time-evolution/018_measures-trajectories-cats-kerr.ipynb)

  - [Steady-State: Optomechanical System in the Single-Photon Strong-Coupling Regime](./tutorials/time-evolution/019_optomechanical-steadystate.ipynb)

  - [Steady-State: Homodyned Jaynes-Cummings emission](./tutorials/time-evolution/020_homodyned-Jaynes-Cummings-emission.ipynb)

  - [Steady-State: Time-dependent (periodic) quantum system](./tutorials/time-evolution/021_quasi-steadystate-driven-system.ipynb)

  - [QuTiPv5 Paper Example: Stochastic Solver - Homodyne Detection](./tutorials/time-evolution/022_v5_paper-smesolve.ipynb)



### Hierarchical Equations of Motion


  - [HEOM 1a: Spin-Bath model (introduction)](./tutorials/heom/heom-1a-spin-bath-model-basic.ipynb)

  - [HEOM 1b: Spin-Bath model (very strong coupling)](./tutorials/heom/heom-1b-spin-bath-model-very-strong-coupling.ipynb)

  - [HEOM 1c: Spin-Bath model (Underdamped Case)](./tutorials/heom/heom-1c-spin-bath-model-underdamped-sd.ipynb)

  - [HEOM 1d: Spin-Bath model, fitting of spectrum and correlation functions](./tutorials/heom/heom-1d-spin-bath-model-ohmic-fitting.ipynb)

  - [HEOM 1e: Spin-Bath model (pure dephasing)](./tutorials/heom/heom-1e-spin-bath-model-pure-dephasing.ipynb)

  - [HEOM 2: Dynamics in Fenna-Mathews-Olsen complex (FMO)](./tutorials/heom/heom-2-fmo-example.ipynb)

  - [HEOM 3: Quantum Heat Transport](./tutorials/heom/heom-3-quantum-heat-transport.ipynb)

  - [HEOM 4: Dynamical decoupling of a non-Markovian environment](./tutorials/heom/heom-4-dynamical-decoupling.ipynb)

  - [HEOM 5a: Fermionic single impurity model](./tutorials/heom/heom-5a-fermions-single-impurity-model.ipynb)

  - [HEOM 5b: Discrete boson coupled to an impurity and fermionic leads](./tutorials/heom/heom-5b-fermions-discrete-boson-model.ipynb)

  - [Hierarchical Equation of Motion Examples](./tutorials/heom/heom-index.ipynb)



### Miscellaneous tutorials


  - [Excitation-number-restricted states: Jaynes-Cummings Chain](./tutorials/miscellaneous/excitation-number-restricted-states-jc-chain.ipynb)

  - [Lecture: Single-photon Interference](./tutorials/miscellaneous/single-photon-interference.ipynb)

  - [qutip-jax JAX backend for qutip](./tutorials/miscellaneous/JAX_backend.ipynb)



## Quantum mechanics lectures with QuTiP

These lecture-style notebooks focus on particular quantum mechanics
topics and analyze them numerically using QuTiP (some more detailed than others).


  - [Lecture 0 - Introduction to QuTiP](./tutorials/lectures/Lecture-0-Introduction-to-QuTiP.ipynb)

  - [Lecture 1 - Vacuum Rabi oscillations in the Jaynes-Cummings model](./tutorials/lectures/Lecture-1-Jaynes-Cumming-model.ipynb)

  - [Lecture 2A - simulation of a two-qubit gate using a resonator as coupler](./tutorials/lectures/Lecture-2A-Cavity-Qubit-Gates.ipynb)

  - [Lecture 2B - Single-Atom-Lasing](./tutorials/lectures/Lecture-2B-Single-Atom-Lasing.ipynb)

  - [Lecture 3A - The Dicke model](./tutorials/lectures/Lecture-3A-Dicke-model.ipynb)

  - [Lecture 3B - Jaynes-Cummings-like model in the ultrastrong coupling regime](./tutorials/lectures/Lecture-3B-Jaynes-Cumming-model-with-ultrastrong-coupling.ipynb)

  - [Lecture 4 - Correlation functions](./tutorials/lectures/Lecture-4-Correlation-Functions.ipynb)

  - [Lecture 5 - Evolution and quantum statistics of a quantum parameter amplifier](./tutorials/lectures/Lecture-5-Parametric-Amplifier.ipynb)

  - [Lecture 6 - Quantum Monte-Carlo Trajectories](./tutorials/lectures/Lecture-6-Quantum-Monte-Carlo-Trajectories.ipynb)

  - [Lecture 7 - Two-qubit iSWAP gate and process tomography](./tutorials/lectures/Lecture-7-iSWAP-gate.ipynb)

  - [Lecture 8 - Adiabatic sweep](./tutorials/lectures/Lecture-8-Adiabatic-quantum-computing.ipynb)

  - [Lecture 9 - Squeezed states of a quantum harmonic oscillator](./tutorials/lectures/Lecture-9-Squeezed-states-of-harmonic-oscillator.ipynb)

  - [Lecture 10 - Cavity-QED in the dispersive regime](./tutorials/lectures/Lecture-10-cQED-dispersive-regime.ipynb)

  - [Lecture 11 - Superconducting Josephson charge qubits](./tutorials/lectures/Lecture-11-Charge-Qubits.ipynb)

  - [Lecture 12 - Decay into a squeezed vacuum field](./tutorials/lectures/Lecture-12-Decay-into-a-squeezed-vacuum-field.ipynb)

  - [Lecture 13 - Resonance flourescence](./tutorials/lectures/Lecture-13-Resonance-flourescence.ipynb)

  - [Lecture 14 - Kerr nonlinearities](./tutorials/lectures/Lecture-14-Kerr-nonlinearities.ipynb)

  - [Lecture 15 - Nonclassically driven atoms (cascaded quantum systems)](./tutorials/lectures/Lecture-15-Nonclassically-driven-atoms.ipynb)

  - [Lecture 16 - Gallery of Wigner functions](./tutorials/lectures/Lecture-16-Gallery-of-Wigner-functions.ipynb)



## Contributing

If you would like to contribute a notebook or report a bug, you may open
an issue or pull request in the
[qutip-tutorials](https://github.com/qutip/qutip-tutorials) GitHub repository.

A few of the notebooks are still maintained in the repository
[qutip-notebooks](https://github.com/qutip/qutip-notebooks) and
a complete archive of older versions of the tutorials is maintained there.