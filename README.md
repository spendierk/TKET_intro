# TKET Intro

On behalf of [Quantinuum](https://www.quantinuum.com/), I invite you to explore tools available in [TKET](https://www.quantinuum.com/developers/tket). TKET is one of the leading open-source quantum software development toolkits (SDKs) designed to compile and optimize quantum programs. It is platform inclusive, allowing it to target the world’s leading quantum hardware, simulators, and other quantum SDKs like Qiskit and PennyLane. It also enhances the performance of other Quantinuum products, such as the quantum computational chemistry and materials science package InQuanto and lambeq, Quantinuum's quantum natural language processing and computational linguistics toolkit. 

The notebooks in this repository called "XX.ipynb" can be opened in a JupyterHub server. To run the notebook in a browser launch Binder: (may take a few minutes to load)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/spendierk/TKET_intro/main).

If you want to run the notebook on your machine, please install all Python packages outlined in "requirements.txt", "runtime.txt", and "apt.txt".


# Introduction to Quantum Computing: Notes
[Here](https://github.com/spendierk/TKET_intro/blob/main/intro_to_QC.pdf) you will find some of my notes on the fundamentals of computation by circuits, logic gates, and the differences between classical bits and qubits. It will also introduce the postulates of quantum computing, providing a foundation for understanding the principles that differentiate quantum computing from classical computing. Furthermore, the notes will cover the Bloch sphere, superposition, complex numbers, measurement, linear algebra, and the quantum circuit model.

# Quirk: A drag-and-drop quantum circuit simulator
[Quirk](https://algassert.com/quirk) is an online tool for simulating and visualizing quantum circuits. It allows users to create quantum circuits by dragging and dropping various quantum gates and measurement tools onto a virtual workspace. Once a circuit has been created, users can simulate its behavior by running it and observing the output.

# Quantum Error Mitigation

```qermit``` is a Python module for [running error-mitigation protocols](https://github.com/CQCL/Qermit) on quantum processors using ```PyTKET```.

You can access the manual [here](https://cqcl.github.io/Qermit/manual/) and a tutorial regarding how to apply ```qermit``` on IBM machines [here](https://github.com/CQCL/IEEE_Quantum_Week/blob/main/Part_3_Qermit.ipynb).
