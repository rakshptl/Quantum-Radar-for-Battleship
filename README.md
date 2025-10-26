# Quantum Radar for Battleship - Qiskit Fall Fest IIT Jodhpur

This repository contains submission for the **Qiskit Fall Fest IIT Jodhpur** hackathon, tackling the 'Quantum Radar for Battleship' challenge. The goal was to implement an interaction-free measurement to find a hidden ship on a 4x4 board with a perfect Elitzur-Vaidman (E.V.) Score.

Our primary solution, detailed in the `Quantum_Radar_for_Battleship.ipynb` notebook, uses the **Quantum Zeno Effect (QZE)** to create a robust, interaction-free 'radar'. This algorithm repeatedly queries a probe qubit, 'freezing' its rotation if a ship is present. This allows us to detect the ship with **zero hits**.

Our simulation over 100 random boards confirmed this, achieving a **perfect infinite E.V. score on 100/100 trials**, demonstrating a provable quantum advantage over a destructive baseline algorithm.

### Video Presentation & Demo
[**Click here to watch video presentation**](https://youtu.be/IM2YvT7Yal4)
