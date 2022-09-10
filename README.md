# Quantum-Entanglement
The very basic and beginner program in Quantum Computing. This short Qiskit code, represents the circuit for entangling two qubits with the help of IBM Quantum Experience.



**NOTE:**

**I have built the circuit using the Quantum Circuit Composer provided by IBM Quantum Experience. To run this Qiskit code, I strongly suggest downloading and setting up Conda
and running the file with the help of Jupyter Notebook.**



For performing it either way, you first need an IBM account. Visit the [website](https://quantum-computing.ibm.com), create an account and get your api key for running it
using Jupyter Notebook.

For achieving entanglement using Quantum Composer, you will be automatically redirected to the Composer page once you sign up. 

Initialize two qubits and bring them into superposition using the 'h' block or the Hadamard gate. Once in superposition, entangle the qubits using the CNOT or the Controlled Not gate 
The qubit which undergoes the Hadamard gate should be the one controlled, i.e q[1] is the control qubit and q[0], the target qubit.

Once completed, look for available real quantum computers in the IBM servers to run your circuit. Add your work into the queue, the computers are busy most of the time.

The circuit should run and you will get the results in under 10 mins irrespective of the computer you allot the task to.

Following would be the resulting histogram

![result](https://github.com/9dubs/test/blob/main/entanglement-result.png)

As you know, the output of two entangled qubits can only be ```00```  or  ```11``` .
