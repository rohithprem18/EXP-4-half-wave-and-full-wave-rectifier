# EXP-4  
## HALF WAVE AND FULL WAVE RECTIFIERS

### AIM  
To study the characteristics of half wave, full wave and bridge rectifiers with and without filter, and calculate the ripple factor, rectification efficiency and percentage regulation.

### COMPONENTS AND EQUIPMENT REQUIRED  
Diodes, Resistor, Transformer, Voltmeter, Ammeter, Breadboard and CRO.

---

## THEORY

A rectifier converts AC to DC and is a key part of any power supply. A diode allows current to flow only in one direction, which makes rectification possible.

---

### **Half Wave Rectifier**

Mains AC is applied to the primary of a step-down transformer.  
Only the positive half cycles of the AC appear across the load because the diode conducts in one direction.  
The peak output voltage is lower than the input by about 0.6 V due to diode drop.

Formulas:  
- \( V_{rms} = \frac{V_m}{2} \)  
- \( V_{dc} = \frac{V_m}{\pi} \)

Where:  
\( V_{rms} \) is the RMS value,  
\( V_{dc} \) is the average output,  
\( V_m \) is the peak output voltage.

---

### **Full Wave Rectifier**

In a full wave rectifier, each half cycle of AC produces a unidirectional current through the load.  
One diode conducts during the positive half cycle and the other during the negative half cycle.  
Again, the peak output is lower than the input by about 0.6 V due to diode drop.

---

### **Bridge Rectifier**

In a bridge rectifier, four diodes are used.  
Two diodes conduct during each half cycle, ensuring current through the load always flows in the same direction.  
The peak output voltage is lower than the input by about 1.2 V due to drops across two diodes.

The ripple factor of a bridge rectifier is the same as a full wave rectifier.

---

### **Filters**

Rectifier output still contains AC components called ripples. Filters reduce these ripples.

Common types: Capacitor input, choke input, RC, CRC, LC, CLC.  
A capacitor input filter is the simplest.  

The capacitor charges to the peak voltage of each cycle and discharges slowly through the load, reducing ripple.

---

### **Rectifier Efficiency**

Rectifier efficiency is the ratio:

\[
\text{Efficiency} = \frac{\text{DC output power}}{\text{AC input power}}
\]

Even ideal rectifiers are less than 100% efficient due to ripple.

---

## PROCEDURE

1. Build the half wave rectifier circuit **without** a capacitor after testing all components.  
2. Switch on the supply. Observe and record the transformer secondary waveform and the rectifier output waveform on the CRO.  
3. Add the capacitor filter, observe the filtered waveforms, and calculate ripple factor, rectification efficiency and regulation. Repeat for multiple capacitor values.  
4. Repeat the same procedure for full wave and bridge rectifiers.

---

## CIRCUIT DIAGRAMS

### Half Wave Rectifier with Filter
![Half Wave Filter](https://github.com/user-attachments/assets/a4c18095-c644-4904-859d-74366ffdd1ba)

### Bridge Rectifier with Filter
![Bridge Filter](https://github.com/user-attachments/assets/3344ec4f-1d93-43fd-b72e-f7d36137e3dc)

---

### HALF WAVE RECTIFIER WAVEFORM
![HWR](https://github.com/user-attachments/assets/1a6892a2-a183-44b9-8b9e-be02018a8657)

### FULL WAVE RECTIFIER WAVEFORM
![FWR](https://github.com/user-attachments/assets/54ad14fa-6fa5-40fe-9a61-e43508017e4d)

---

## RESULT  
Input and output waveforms of half wave, full wave and bridge rectifiers with and without filters are observed and plotted.

