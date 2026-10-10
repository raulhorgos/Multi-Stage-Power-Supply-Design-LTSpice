# Multi-Stage Power Supply Design | LTSpice 

Designed a multi-output power supply converting 220V AC (50Hz) into three regulated DC
outputs: 12V, 5V, and 3.3V. The calculus was done by using SMath Solver for efficient and
fast computations and the implementation of the whole circuit was done in LTSpice.

-Implemented a full-bridge rectifier with capacitive filtering, utilizing 7000µF capacitors to
minimize voltage ripple.

-Developed a discrete Linear Regulator using a BJT transistor and Zener reference to
provide a 12V/500mA output.

-Integrated an IC for the 5V output with a proper heat sink.

-Designed a Buck Converter with a closed-loop control system to step down voltage to
3.3V/2A, operating at 100kHz with >90% target efficiency
