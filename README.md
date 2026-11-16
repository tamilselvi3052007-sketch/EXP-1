## EXPERIMENT NO. 1 – VERIFICATION OF KIRCHHOFF'S LAWS

| **Name:**\ | MOHANAPRIYA G | **Reg. No.:** | 26018306 |
|---|---|---|---|
| **Date:** |16-11-2026 | **Batch / Section:** |26ODJ121 |

---

## AIM

a. To verify Kirchhoff's Voltage Law (KVL) for the given circuit.

b. To verify Kirchhoff's Current Law (KCL) for the given circuit.

## APPARATUS REQUIRED

| S. No. | Component | Range / Rating | Quantity |
|:---:|:---:|:---:|:---:|
| 1 | Resistor | 1 kΩ | 3 |
| 2 | DC Voltmeter | 0–30 V | 3 |
| 3 | DC Ammeter | 0–0.2 A | 3 |
| 4 | Breadboard | — | 1 |
| 5 | Regulated Power Supply (RPS) | 0–30 V | 1 |
| 6 | Connecting wires | As required | As required |
| 7 | Simulation software | Proteus Design Suite | 1 |

## THEORY

**Kirchhoff's Voltage Law (KVL):** The algebraic sum of all voltage rises and voltage drops around any closed loop in an electrical circuit is zero.

**Kirchhoff's Current Law (KCL):** The algebraic sum of currents at any node is zero. In other words, the total current entering a node is equal to the total current leaving the node.

## PROCEDURE

### A. Verification of KVL

1. Connect the circuit as shown in the KVL circuit diagram.
2. Ensure that the RPS output is set to zero volts before switching it on.
3. Check that all meters are correctly connected and set to their zero positions.
4. Switch on the RPS and gradually set the required input voltage within the specified range.
5. Measure and record the voltage across each resistor using the voltmeters.
6. Repeat the measurements for different input-voltage values and tabulate the readings.

### B. Verification of KCL

7. Connect the circuit as shown in the KCL circuit diagram.
8. Ensure that the RPS output is set to zero volts before switching it on.
9. Check that all meters are correctly connected and set to their zero positions.
10. Switch on the RPS and gradually set the required input voltage within the specified range.
11. Measure and record the current in each branch using the ammeters.
12. Repeat the measurements for different input-voltage values and tabulate the readings.

## CIRCUIT DIAGRAMS

### A. KVL circuit diagram

*[ Insert the KVL circuit diagram here ]*
<img width="718" height="836" alt="KVL DRAW" src="https://github.com/user-attachments/assets/24e85c5a-3f93-442a-bb42-56101dbbb1f9" />


**Figure 1:** KVL verification circuit

### B. KCL circuit diagram

*[ Insert the KCL circuit diagram here ]*
<img width="718" height="857" alt="KCL DRAW" src="https://github.com/user-attachments/assets/a8d6ef35-d0dd-4f91-8647-5fe9edfa157a" />


**Figure 2:** KCL verification circuit

## SIMULATION USING PROTEUS

Build the KVL and KCL circuits in Proteus using the same resistor values and supply voltage as the hardware circuit. Place DC voltmeters and DC ammeters from the Virtual Instruments mode, run the simulation, and paste a screenshot showing the meter readings for each circuit.

### A. KVL simulation

*[ Paste the Proteus KVL simulation screenshot here ]*
<img width="945" height="587" alt="Screenshot 2026-10-14 150930" src="https://github.com/user-attachments/assets/6275ae10-0624-41da-9e95-37766692071b" />


**Figure 3:** Proteus simulation of KVL circuit

### B. KCL simulation

*[ Paste the Proteus KCL simulation screenshot here ]*
<img width="1920" height="1080" alt="Screenshot 2026-11-15 194918" src="https://github.com/user-attachments/assets/75246c15-a48f-42d5-96fc-70ea7e589be8" />

**Figure 4:** Proteus simulation of KCL circuit

## OBSERVATION AND TABULATION

### A. KVL – Voltage measurements

| S. No. | Supply voltage Vs (V) | VR1 (V) | VR2 (V) | VR3 (V) | VR1 + VR2 + VR3 (V) |
|:---:|:---:|:---:|:---:|:---:|:---:|
| Theoritical | 100 | 1668 V | 27.8 V | 55.6 V | 100.05 |
| Practical | 100 | 16.7 V| 27.8 V | 55.6 V | 100.1 |

### B. KCL – Current measurements

| S. No. | Supply voltage Vs (V) | Total current It (A) | Branch current I1 (A) | Branch current I2 (A) | Branch current I3 (A) | I1 + I2 + I3 (A) |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Theoritical | -1.48 A | 1.85 A | 0.56 A | 52.63 | | |
| Practical |1.58 | 1.05 A | 0.53 A | 52.6 A | | |

## CALCULATIONS

### A. KVL

According to KVL, **Vs = VR1 + VR2 + VR3**.

Substitute the observed values and verify that the algebraic sum of the voltage drops is approximately equal to the supply voltage.

*[ Paste the KVL calculation screenshot here ]*
<img width="1185" height="1600" alt="KVL" src="https://github.com/user-attachments/assets/b7e01e52-12db-4022-8340-ef3997844ff6" />


**Figure 5:** KVL calculation

### B. KCL

According to KCL, **It = I1 + I2 + I3**.

Substitute the observed values and verify that the total current entering the node is approximately equal to the sum of the branch currents.

*[ Paste the KCL calculation screenshot here ]*
<img width="1181" height="1600" alt="KCL" src="https://github.com/user-attachments/assets/8413e927-d7e3-4987-896d-2f23d7600dc5" />


**Figure 6:** KCL calculation

## RESULT

Thus, Kirchhoff's Voltage Law (KVL) and Kirchhoff's Current Law (KCL) were verified experimentally and through Proteus simulation for the given circuits.
