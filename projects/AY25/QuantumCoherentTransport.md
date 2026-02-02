# Quantum Coherent Transport

**Repo Link:** [Click Me](https://github.com/stark-069/quantum-graph-transport)

A simulation of quantum coherent transport on an 8-node graph network using Qiskit, developed for the IISc-IBM Qiskit Fall Fest 2025 challenge.

## Key Principles

* **Coherent Transport:** Modeled as the transfer of a quantum state $|X\rangle$ from Node A to Node B via intermediate nodes.
* **Graph Topology:** Simulates an 8-node directed graph with specific parity constraints.
* **Circuit Depth Optimization:** Minimizes gate count while ensuring high-fidelity state transfer.
* **Ancilla Verification:** Uses an ancilla qubit to verify successful transport path logic.

## Features

* 8-Node Graph topology visualization
* Automated state verification and histogram analysis
* Path asymmetry detection (experimentally witnessing path length differences)
* Scalable circuit generation for graph traversal

## Technologies Used

* Qiskit
* Python
* Matplotlib
* NumPy

## References

* Christandl, M., Datta, N., Ekert, A., & Landahl, A. (2004). Perfect state transfer in quantum spin networks. Physical Review Letters, 92(18), 187902.
* Douglas, B. L., & Wang, J. B. (2009). Efficient quantum circuit implementation of quantum walks. Physical Review A, 79(5), 052335.
* Kendon, V. M., & Tamon, C. (2011). Perfect state transfer in quantum walks on graphs. Journal of Computational and Theoretical Nanoscience, 8(3), 422-433.

## Author

_Abhiroop Gohar, BTech Engineering Physics, IIT Indore, Class of 2028_
