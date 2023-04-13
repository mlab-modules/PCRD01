# PCB

Board size: 50.29x29.97 mm (1.98x1.18 inches)

- This is the size of the rectangle that contains the board
- Thickness: 1.6 mm (63 mils)
- Material: FR4
- Finish: None
- Layers: 2
- Copper thickness: 35 µm

Solder mask: TOP / BOTTOM

- Color: Green

Silk screen: TOP / BOTTOM

- Color: White


Stackup:

| Name                 | Type                 | Color            | Thickness | Material        | Epsilon_r | Loss tangent |
|----------------------|----------------------|------------------|-----------|-----------------|-----------|--------------|
| F.SilkS              | Top Silk Screen      |                  |           |                 |           |              |
| F.Paste              | Top Solder Paste     |                  |           |                 |           |              |
| F.Mask               | Top Solder Mask      |                  |        10 |                 |           |              |
| F.Cu                 | copper               |                  |        35 |                 |           |              |
| dielectric 1         | core                 |                  |      1510 | FR4             |       4.5 |        0.020 |
| B.Cu                 | copper               |                  |        35 |                 |           |              |
| B.Mask               | Bottom Solder Mask   |                  |        10 |                 |           |              |
| B.Paste              | Bottom Solder Paste  |                  |           |                 |           |              |
| B.SilkS              | Bottom Silk Screen   |                  |           |                 |           |              |

# Important sizes

Clearance: 0.2 mm (8 mils)

Track width: 0.4 mm (16 mils)

- By design rules: 0.1 mm (4 mils)

Drill: 0.75 mm (30 mils)

- Vias: 0.75 mm (30 mils) [Design: 0.6 mm (24 mils)]
- Pads: 1.0 mm (39 mils)
- The above values are real drill sizes, they add 0.1 mm (4 mils) to plated holes (PTH)

Via: 0.89/0.64 mm (35/25 mils)

- By design rules: 0.89/0.51 mm (35/20 mils)
- Micro via: no [0.51/0.13 mm (20/5 mils)]
- Buried/blind via: no
- Total: 25 (thru: 25 buried/blind: 0 micro: 0)

Outer Annular Ring: 0.07 mm (3 mils)

- By design rules: 0.26 mm (10 mils)

Eurocircuits class: 10A
- Using min drill 0.75 mm for an OAR of 0.07 mm


# General stats

Components count: (SMD/THT)

- Top: 0/8 (THT)
- Bottom: 29/2 (SMD + THT)

Defined tracks:

- 0.13 mm (5 mils)
- 0.2 mm (8 mils)
- 0.3 mm (12 mils)
- 0.4 mm (16 mils)
- 0.5 mm (20 mils)

Used tracks:

- 0.4 mm (16 mils) (57) defined: yes
- 0.5 mm (20 mils) (76) defined: yes

Defined vias:


Used vias:

- 0.89/0.64 mm (35/25 mils) (Count: 25, Aspect: 1.8 A) defined: no

Holes (excluding vias):

- 0.89 mm (35 mils) (27)
- 3.0 mm (118 mils) (4)

Oval holes:


Drill tools (including vias and computing adjusts and rounding):

- 0.75 mm (30 mils) (25)
- 1.0 mm (39 mils) (27)
- 3.1 mm (122 mils) (4)




