## EXPERIMENT NO. 1 – VERIFICATION OF KIRCHHOFF'S LAWS

| **Name:** |Sushmitha S| **Reg. No.:** |26018220 |
| **Date:** |13-11-2026 | **Batch / Section:** |260DJ153|

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
<img width="1600" height="1406" alt="WhatsApp Image 2026-11-13 at 9 20 23 PM" src="https://github.com/user-attachments/assets/1725c492-0207-449e-93f9-73376c56d629" />


**Figure 1:** KVL verification circuit

### B. KCL circuit diagram

<img width="1575" height="1126" alt="WhatsApp Image 2026-11-13 at 9 20 24 PM (2)" src="https://github.com/user-attachments/assets/2ec9e686-e74b-4b88-b49c-a78534df90b9" />


**Figure 2:** KCL verification circuit

## SIMULATION USING PROTEUS

Build the KVL and KCL circuits in Proteus using the same resistor values and supply voltage as the hardware circuit. Place DC voltmeters and DC ammeters from the Virtual Instruments mode, run the simulation, and paste a screenshot showing the meter readings for each circuit.

### A. KVL simulation

<img width="1920" height="1080" alt="Screenshot (11)" src="https://github.com/user-attachments/assets/1c4c1655-a165-4b0e-8b65-6793211ec5d6" />


**Figure 3:** Proteus simulation of KVL circuit

### B. KCL simulation

<img width="1092" height="732" alt="WhatsApp Image 2026-11-13 at 4 16 37 PM" src="https://github.com/user-attachments/assets/3a871137-6087-4b65-a899-2a705e7bcd1d" />


**Figure 4:** Proteus simulation of KCL circuit

## OBSERVATION AND TABULATION

### A. KVL – Voltage measurements

| S. No. | Supply voltage Vs (V) | VR1 (V) | VR2 (V) | VR3 (V) | VR1 + VR2 + VR3 (V) |
<img width="1600" height="819" alt="WhatsApp Image 2026-11-13 at 9 20 24 PM" src="https://github.com/user-attachments/assets/ce5559df-1d7f-4e0a-ac49-66c2ac0da9e1" />


### B. KCL – Current measurements

| S. No. | Supply voltage Vs (V) | Total current It (A) | Branch current I1 (A) | Branch current I2 (A) | Branch current I3 (A) | I1 + I2 + I3 (A) |
<img width="1600" height="900" alt="WhatsApp Image 2026-11-13 at 9 20 25 PM" src="https://github.com/user-attachments/assets/40a7517a-713a-4882-88f7-05b58c69ab49" />

## CALCULATIONS

### A. KVL

According to KVL, **Vs = VR1 + VR2 + VR3**.

Substitute the observed values and verify that the algebraic sum of the voltage drops is approximately equal to the supply voltage.

<img width="1380" height="1600" alt="WhatsApp Image 2026-11-13 at 9 20 23 PM (1)" src="https://github.com/user-attachments/assets/50e5b3a1-edce-4912-bd7a-d535e0a4b73b" />


**Figure 5:** KVL calculation

### B. KCL

According to KCL, **It = I1 + I2 + I3**.

Substitute the observed values and verify that the total current entering the node is approximately equal to the sum of the branch currents.

<img width="899" height="1599" alt="WhatsApp Image 2026-11-13 at 9 20 24 PM (1)" src="https://github.com/user-attachments/assets/213a5e45-520c-4983-864e-ae515c0fef9f" />


**Figure 6:** KCL calculation

## RESULT

Thus, Kirchhoff's Voltage Law (KVL) and Kirchhoff's Current Law (KCL) were verified experimentally and through Proteus simulation for the given circuits.
