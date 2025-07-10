# FLC-Quantum-Workshop-25
Just a big Jupyter notebook with what we were up to in July 2025
This README summarizes what you learned during our **Intro to Quantum Computing** workshop using **Qiskit**, and provides pointers for further exploration.

---

## 🧭 What We Covered

### 🧑‍🏫 Day 1: Foundations of Quantum Computing

We began with a conceptual understanding of:

- **Why quantum computing matters**
  - Solving problems classical computers can’t solve efficiently (e.g. factoring, optimization)
  - Natural fit for simulating quantum systems
  - Novel computation models beyond binary logic

- **Key concepts:**
  - Qubits vs. classical bits
  - Superposition and the Bloch sphere
  - Global vs. relative phase
  - Measurement and the collapse of a quantum state

- **Qiskit Basics:**
  - Representing qubit states manually using `Statevector`
  - Visualizing qubit states with Grokking the Bloch

---

## 🔄 Day 2: Circuits, Gates, and Entanglement

We transitioned to using **quantum circuits** with Qiskit:

- **Basic quantum gates:** `X`, `Y`, `Z`, `H`, `Rx`, `Ry`, `Rz`
- **Visualization of how each gate rotates or flips the Bloch vector**


---

## 🌀 Day 3: Quantum Entanglement and Intro to Teleportation

We explored:
- **Entanglement** using `H` and `CNOT` gates to create **Bell states**
- **Measuring entangled qubits** to observe correlations
- **Bloch sphere limitations for entangled states**
- Running jobs on **real IBM quantum hardware**
---

## 🧮 Day 4: Quantum Algorithms

- **Quantum teleportation protocol**
  - Shared Bell pair between Alice and Bob
  - Sending an unknown quantum state using **entanglement** + 2 classical bits
  - Why no-cloning theorem is upheld
- **Hands-on Qiskit teleportation demo**

We implemented our **first quantum algorithm**:

### ✅ Deutsch's Algorithm
- Learn about **oracles** and how they behave like black-box functions
- Showed how quantum algorithms can solve certain problems in fewer steps than classical ones
- Implemented and ran Deutsch’s algorithm in Qiskit
- Importance of **ancilla qubits** and intermediate measurements
- **Grover's Algorithm** (quantum search)
---

## 🚀 Optional Exploration (If You’re Curious)

- **Shor's Algorithm**
- **Quantum Fourier Transform**
- **Error correction & decoherence**


---

## 🧰 Qiskit Tools We Used

- `QuantumCircuit`
- `Statevector` 
- `transpile()` and `backend` selection
- `plot_bloch_multivector()`, `plot_histogram()`
- `QiskitRuntimeService` to submit to real machines

---

## 📚 Suggested Next Steps

- Revisit your Jupyter notebooks and annotate what each line does
- Try modifying circuits and re-running them to test your understanding
- Watch the Qiskit YouTube tutorials or complete the Qiskit Textbook online
- Explore IBM’s Quantum Composer GUI for visual learning

---

Thanks for participating, and welcome to the quantum future! 🧪⚛️

