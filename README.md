# Current-and-Voltage-Curve-Tracer
The system plots the leakage current with respect to voltage across the drain-source of MOSFETS, collector-emitter of BJTS and P-N junction of diodes. 
The system incorporates three subsystems comprised of LabVIEW as the control center for issuing commands and analyzing data, 
a PIC microcontroller for gathering data of a DUT, device under test, and MySQL for remote data storage and analyzation via TCP/IP protocol.
The result of system execution yields a graphical display that describes the DUT’s leakage current as voltage is increased. 
