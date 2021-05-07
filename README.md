Grilles v2.0 in FRAC format for BugBrand Modular System

With the permission of Émilie Gillet (Mutable Instruments), Scrotum Lab made this version of Grids in FRAC format compatible with the BugBrand Modular System.

In this repository you will find:

• The PCB file in Diptrace format.
• The Schematics in Diptrace format.
• The front panel as PCB in Diptrace format.
• All GERBER files
• BOM with all references
• Pick'n'place file: it is primordial that you first ask permission to Emilie Gillet / Mutable Instruments before you go to manufacturing PCBs!!!

The schematics in this version include the part of the circuit needed for MIDI clock input added to the front panel.

EDIT: ideally the circuit would need to be modified so the GATE OUTS are totally conform to the BugBrand standard of +10V. It would mean doubling the signals at all outputs of the shift register (74HC595D) by adding for instance some opAmps to the circuit (multiplying by 2). Means changing the schematics and PCB circuit accordingly.

![Grilles-v2 0-768x1152](https://user-images.githubusercontent.com/39232489/90115733-c62c3a00-dd54-11ea-8b27-cf4a8caaf2df.jpg)
