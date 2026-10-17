# Multiply Accumulate

A four quadrant multipler based on the MC1496.

* Module size: 4HP (20 mm)
* Power: 10mA (+12V); 10mA (-12V)

!!! repository "Project Source"

    The project files, including schematic and layout, are available on [github](https://github.com/xdylanm/multiply-accumulate)

## Features

This module implements a multiplier based on the Gilbert cell topology. The design is a combination of the Yusynth version and the datasheet, and includes

* analog mulitplication of two DC-coupled signals, with one input controlled by an attenuverter 
* a summing input for the third channel, with an attenuverter to adjust the input level

This combination can function as a balanced modulator, VCA, and mixer. 

## Documentation

[Design](design.md)

[Assembly Guide](assembly.md)

[Schematic](assets/schematic.pdf)

## References

1. Yves Usson, "Dual balanced modulator (ring modulator)," [yusynth.net](https://yusynth.net/Modular/EN/RINGMOD/index.html)
2. MC1496 Datasheet, [onsemi.com](https://www.onsemi.com/pdf/datasheet/mc1496-d.pdf)