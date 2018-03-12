# DMMs

Information about digital multimeters, especially used models of interest to volt-nuts.


## Models with 6.5-digit resolution

### General info:

| Make | Model | Introduced | Comms | Image |
|---|---|---|---|---|
| HP | 3456A | 1980? | GPIB | ![](media/hp-3456a.jpg) |
| HP | 3457A | 1985? | GPIB | ![](media/hp-3457a.jpg) |
| HP / Agilent / Keysight | 34401A | 1991? | GPIB, RS-232 | ![](media/hp-34401a.jpg) |
| Keithley | 192 | 1982? | ? | ![](media/keithley-192.jpg) |
| Keithley | 193 | 1985? | GPIB | ![](media/keithley-193.jpg) |
| Keithley | 196 | 1986? | GPIB | ![](media/keithley-196.jpg) |
| Keithley | 199 | 1986? | GPIB | ![](media/keithley-199.jpg) |
| Keithley | 2000 | | GPIB, RS-232 | ![](media/keithley-2000.jpg) |
| Keithley | 2015 | | GPIB, RS-232 | ![](media/keithley-2015.jpg) |
| ~~Keithley~~ | ~~2100~~ | | | ![](media/keithley-2100.jpg) |
| Fluke | 8502A | | GPIB (opt.) | ![](media/fluke-8502a.jpg) |
| Fluke | 8505A | | GPIB (opt.) | ![](media/fluke-8505a.jpg) |
| Fluke | 8520A | | GPIB | ![](media/fluke-8520a.jpg) |
| Fluke | 8845A | | | |
| Fluke | 8846A | | | |
| Tektronix | DMM4050 | | | |
| Datron | 1061A | | GPIB | ![](media/datron-1061a.jpg) |
| Datron | 1062 | | GPIB | ![](media/datron-1062.jpg) |
| Datron | 1065A | | | ![](media/datron-1065a.jpg) |
| Prema | 6001 | | | ![](media/prema-6001.jpg) |
| Solartron | 7150 | | GPIB | ![](media/solartron-7150.jpg) |
| Solartron | 7151 | | GPIB | ![](media/solartron-7151.jpg) |

Notes:
- "The rebadged Keithley 2100 was quite terrible" [[1](https://www.eevblog.com/forum/chat/bench-multimeter-(another)/msg244830/#msg244830)]
- The Tektronix DMM4050 is a re-badge of the Fluke 8846A [[1](http://www.eevblog.com/forum/metrology/the-ltflu-(aka-sza263)-reference-zener-diode-circuit/msg609636/#msg609636)]

### Range info:

| Make | Model | Range scheme | A/D counts | Max value |
|---|---|---|---|---|
| HP | 3456A | 1x, 10x, ... | 1,200,000 | 1.199999 |
| HP | 3457A | 3x, 30x, ... | | 3.030000 |
| HP/Agilent | 34401A | 1x, 10x, ... | 1,200,000 | |
| Keithley | 192 | 2x, 20x, ... | 2,000,000 | 1.999999 |
| Keithley | 193 | 2x, 20x, ... | 2,200,000 | 2.199999 |
| Keithley | 196 | 3x, 30x, ... | 3,030,000 | |
| Keithley | 2000 | 1x, 10x, ... | | "120% overrange" |
| Keithley | 2015 | 1x, 10x, ... | | "120% overrange" |
| Fluke | 8502A | | | |
| Fluke | 8505A | | | |
| Fluke | 8520A | | | |
| Datron | 1061A | | 1,999,999 | |
| Datron | 1062 | | 1,999,999 | |
| Datron | 1065A | | 1,999,999 | |
| Prema | 6001 | | | |
| Solartron | 7150 | | 2,350,000 | |

### DC Volts info:

| Make | Model | Best res. (range) | Hi-Z (value) |
|---|---|---|---|
| HP | 3456A | 100nV (100mV) | 100mV, 1V, 10V |
| HP | 3457A | 10nV (30mV) | 30mV, 300mV, 3V |
| HP/Agilent | 34401A | 100nV (100mV) | 100mV, 1V, 10V (>10G) |
| Keithley | 192 | 1uV (2V<sup>*</sup>) | 200mV, 2V, 20V (>1G) |
| Keithley | 193 | 100nV (200mV) | 200mV, 2V |
| Keithley | 196 | 100nV (300mV) | 300mV, 3V (>1G) |
| Keithley | 2000 | 100nV (100mV) | 100mV, 1V, 10V (>10G) |
| Keithley | 2015 | | |
| Fluke | 8502A | | |
| Fluke | 8505A | | |
| Fluke | 8520A | | |
| Datron | 1062 | | |
| Prema | 6001 | | |
| Solartron | 7150 |  | 200mV, 2V (>10G) |

Note:
- Keithley 192 has no 0.2V range in 6.5-digit mode (best 6.5-digit resolution is 1uV in 2V range).

### Calibration info:

| Make | Model | Cal methods |
|---|---|---|
| HP | 3456A | Trimpots |
| HP | 3457A | Front-panel, GPIB |
| HP/Agilent | 34401A | Front-panel, GPIB |
| Keithley | 192 | Trimpots |
| Keithley | 193 | Front-panel, GPIB |
| Keithley | 196 | Front-panel, GPIB |
| Keithley | 2000 | Front-panel, GPIB |
| Keithley | 2015 | Front-panel, GPIB |
| Fluke | 8502A | |
| Fluke | 8505A | |
| Fluke | 8520A | |
| Datron | 1062 | |
| Prema | 6001 | |

Notes:
- The 34401A's calibration counts each range as a "calibration", so a full calibration will increase the count by 35.

Ohms calibration info:

| Make | Model | Valid cal. input range |
|---|---|---|
| HP | 3456A | (arbitrary) |
| HP | 3457A | (See note<sup>*</sup>) |
| HP/Agilent | 34401A | 0.9x to 1.1x |
| Keithley | 192 | (must less than full-scale, e.g. 1.999999) |
| Keithley | 193 | (See note<sup>*</sup>) |
| Keithley | 196 | (See note<sup>*</sup>) |
| Keithley | 2000 | 0.9x to 1.1x |
| Keithley | 2015 | 0.9x to 1.1x |
| Fluke | 8502A | |
| Fluke | 8505A | |
| Fluke | 8520A | |
| Datron | 1062 | |
| Prema | 6001 | |

Notes:
- The 3457A allows entering the exact value of the calibration source, but I'm not sure of the allowed range of values.  The service manual lists the following "required equipment" for calibration:
  - 30R (+/-0.2%), 300R (+/-0.02%), 3K (+/-0.003%), 30K (+/-0.001%), 300K (+/-0.001%), 3Meg (+/-0.002%), 30Meg (+/-0.009%)
- The Keithley 192 calls for 1.9x calibration values.  The manual also specifies "To prevent AD saturation, peak AC+DC value must be less than full scale on any range".
- The Keithley 193 calls for 1.9x calibration values.  However, it allows entering arbitrary values.
- The Keithley 196 calls for 1.9x calibration values.  However, it allows entering arbitrary values.

### Additional resources:

- HP 3456A
  - [xDevs.com](https://xdevs.com/fix/hp3456a/)
- HP 3457A
  - [xDevs.com](https://xdevs.com/article/hp3457a/)
- Keithley 199
  - [Re-engineered digital board](https://www.eevblog.com/forum/repair/keithley-199-digital-board-replacement/)
  - [Replacing 1N4579 ref. zener with LM399](https://www.eevblog.com/forum/chat/bench-multimeter-(another)/msg265846/#msg265846)



## Models with 5.5-digit resolution

### General info:

| Make | Model | Introduced | Comms | Image |
|---|---|---|---|---|
| Keithley | 195A | 1984? | GPIB | ![](media/keithley-195a.jpg) |
| Keithley | 199<sup>*</sup> | 1988? | GPIB | ![](media/keithley-199.jpg) |
| Fluke | 8840A | | | |
| Fluke | 8842A | | | |
| Datron | 1061 | | | ![](media/datron-1061.jpg) |
| Datron | 1065 | | | ![](media/datron-1065.jpg) |

Notes:
- The Keithley 199 is a scanner.

### Range info:

| Make | Model | Range scheme | A/D counts | Max value |
|---|---|---|---|---|
| Datron | 1061 | 2x, 20x, ... | 199,999 | |
| Datron | 1065 | 2x, 20x, ... | 199,999 | |



## Models with 7.5-digit resolution

### General info:

| Make | Model | Introduced | Comms | Image |
|---|---|---|---|---|
| Datron | 1071 | | | ![](media/datron-1071.jpg) |
| Datron | 1072 | | | ![](media/datron-1072.jpg) |
| Datron | 1081 | | | ![](media/datron-1081.jpg) |
| Datron | 1082 | | | ![](media/datron-1082.jpg) |
| HP/Agilent/Keysight | 34420A | | | |
| Keithley/Tektronix | 2010 | | | |
| Keithley/Tektronix | 2001 | | | |

### Range info:

| Make | Model | Range scheme | A/D counts | Max value |
|---|---|---|---|---|
| Datron | 1071 | 2x, 20x, ... | 19,999,999 | |
| Datron | 1072 | 2x, 20x, ... | 19,999,999 | |
| Datron | 1081 | 2x, 20x, ... | 19,999,999 | |
| Datron | 1082 | 2x, 20x, ... | 19,999,999 | |


## Models with 8.5-digit resolution

### General info:

| Make | Model | Introduced | Comms | Image |
|---|---|---|---|---|
| Datron | 1271 | | | ![](media/datron-1271.jpg) |
| Datron | 1281 | | | ![](media/datron-1281.jpg) |
| HP/Agilent/Keysight | 3458A | | | |
| Keithley/Tektronix | 2002 | | | |


### Additional resources:

- Datron 1281
  - [xDevs.com](https://xdevs.com/fix/d1281/)
- HP/Agilent/Keysight 3458A
  - [xDevs.com](https://xdevs.com/fix/hp3458a/) [second unit](https://xdevs.com/fix/hp3458a_u2/) [third unit](https://xdevs.com/fix/hp3458a_u3/) [tweaks investigation](https://xdevs.com/article/hp3458b/) [4th unit](https://xdevs.com/fix/hp3458a_u4/)
