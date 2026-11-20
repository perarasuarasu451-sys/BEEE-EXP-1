## EXPERIMENT NO. 1 – VERIFICATION OF KIRCHHOFF'S LAWS

| **Name: PERARASSU K** |  | **Reg. No.: 212225100034** |  |
|---|---|---|---|
| **Date: 20-10-2026** | | **Batch / Section: 26OD2200** | |

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

<img width="1137" height="755" alt="KVL" src="https://github.com/user-attachments/assets/7601ab81-3cdc-4a4f-ad43-1cc8447366a0" />

**Figure 1:** KVL verification circuit

### B. KCL circuit diagram

<img width="821" height="595" alt="image" src="https://github.com/user-attachments/assets/ef486cd3-fffa-4c38-afca-1cc02ec8175a" />

**Figure 2:** KCL verification circuit

## SIMULATION USING PROTEUS

Build the KVL and KCL circuits in Proteus using the same resistor values and supply voltage as the hardware circuit. Place DC voltmeters and DC ammeters from the Virtual Instruments mode, run the simulation, and paste a screenshot showing the meter readings for each circuit.

### A. KVL simulation

<img width="1508" height="2496" alt="IMG_20261021_143438_1" src="https://github.com/user-attachments/assets/90914237-d339-4268-90e3-0b8abae3b2ca" />
<img width="1500" height="836" alt="IMG_20261021_175449" src="https://github.com/user-attachments/assets/ee5c0563-26be-4184-888e-bb79ea9f6564" />

**Figure 3:** Proteus simulation of KVL circuit

### B. KCL simulation

<img width="1508" height="1796" alt="IMG_20261021_175438" src="https://github.com/user-attachments/assets/30fd581f-3cfd-4809-ac85-d54274c50791" />

**Figure 4:** Proteus simulation of KCL circuit

## OBSERVATION AND TABULATION

### A. KVL – Voltage measurements

| S. No. | Supply voltage Vs (V) | VR1 (V) | VR2 (V) | VR3 (V) | VR1 + VR2 + VR3 (V) |
|:---:|:---:|:---:|:---:|:---:|:---:|
| Theoritical |  |  |  | | |
| Practical | | | | | |

### B. KCL – Current measurements

| S. No. | Supply voltage Vs (V) | Total current It (A) | Branch current I1 (A) | Branch current I2 (A) | Branch current I3 (A) | I1 + I2 + I3 (A) |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Theoritical | | | | | | |
| Practical | | | | | | |

## CALCULATIONS

### A. KVL

According to KVL, **Vs = VR1 + VR2 + VR3**.

Substitute the observed values and verify that the algebraic sum of the voltage drops is approximately equal to the supply voltage.

<img width="1548" height="1044" alt="IMG_20261021_175507" src="https://github.com/user-attachments/assets/e928e228-a748-42b9-a91d-69efc53daa99" />

**Figure 5:** KVL calculation

### B. KCL

According to KCL, **It = I1 + I2 + I3**.

Substitute the observed values and verify that the total current entering the node is approximately equal to the sum of the branch currents.

<img width="1548" height="1536" alt="IMG_20261021_175500" src="https://github.com/user-attachments/assets/bdaca5da-cf10-4656-b653-9fc3dd31b847" />

**Figure 6:** KCL calculation

## RESULT

Thus, Kirchhoff's Voltage Law (KVL) and Kirchhoff's Current Law (KCL) were verified experimentally and through Proteus simulation for the given circuits.
