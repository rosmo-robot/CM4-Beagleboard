# CM4-Beagleboard
CM4 carrier in Beaglebone footprint

![To do](https://github.com/rosmo-robot/CM4-Beagleboard/blob/main/CM4-Beaglebone/Image/CM4-Beagle.png)

![pins](https://beagleboard.org/static/images/cape-headers.png)

![CM4](https://git.beagleboard.org/sam_uk/cm4-carrier/-/raw/master/CM4.png)

[Pin reference doc](https://docs.google.com/spreadsheets/d/1fE-AsDZvJ-bBwzNBj1_sPDrutvEvsmARqFwvbw_HkrE/edit#gid=1518010293)

| BeagleBone Black P8 Pin	 | Function   | CM4 Pin  |
|---|---|---|
| P8_1  | DGND  |  1 |
|  P8_2  | DGND  |  2 |
|  P8_3  | mmc3_dat6  | 25  |
| P8_4  | mmc3_dat7  |  26 |
|  P8_5  | mmc3_dat2  | 27  |
|  P8_6  | mmc3_dat3  |   |
|   P8_7 | mcasp1_axr14  |   |
|  P8_8  | mcasp1_axr15  |   |
|  P8_9  | xref_clk1  |   |
|  P8_10  | mcasp1_axr13  |   |
|  P8_11  | vin1a_d7  |   |
|  P8_12  | vin1a_d6  |   |
|  P8_13  | ehrpwm2B  |   |
|   P8_14 |  vin2a_d12 |   |
|   P8_15 | vin2a_d2  |   |
| P8_16 | vin2a_d21  |             |
| P8_17 | vout1_d18  |    |
| P8_18 | vin2a_d8  |   |
| P8_19 |  ehrpwm2A |   |
| P8_20 |mmc3_cmd   |   |
| P8_21 | mmc3_clk  |   |
| P8_22 | mmc3_dat5  |   |
| P8_23 | mmc3_dat4  |   |
| P8_24 | mmc3_dat1  |   |
| P8_25 | mmc3_dat0  |   |
| P8_26 | vin2a_d20  |   |
| P8_27  | vout1_vsync  |   |
|  P8_28 |  vout1_clk |   |
|  P8_29 | vout1_hsync  |   |
|  P8_30 | vout1_de  |   |
|  P8_31 | vout1_d14  |   |
|  P8_32 |  vout1_d15 |   |
|  P8_33 |  vout1_d13 |   |
|  P8_34 |  vout1_d11 |   |
|  P8_35 | vout1_d12  |   |
|  P8_36 |  vout1_d10 |   |
|  P8_37 |  vout1_d8 |   |
|  P8_38 |  vout1_d9 |   |
|  P8_39 |vout1_d6   |   |
|  P8_40 | vout1_d7  |   |
|  P8_41 |  vout1_d4 |   |
|  P8_42| vout1_d5  |   |
|  P8_43|  vout1_d2 |   |
|  P8_44 | vout1_d3  |   |
|  P8_45 | vout1_d0  |   |
|  P8_46 | vout1_d1  |   |


| BeagleBone Black P9 Pin	 | Function   | CM4 Pin  |
|---|---|---|
| P9_1  |   |   |
|  P9_2  |   |   |
|  P9_3  |   |   |
| P9_4  |   |   |
|  P9_5  |   |   |
|  P9_6  |   |   |
|   P9_7 |   |   |
|  P9_8  |   |   |
|  P9_9  |   |   |
|  P9_10  |   |   |
|  P9_11  |   |   |
|  P9_12  |   |   |
|  P9_13  |   |   |
|   P9_14 |   |   |
|   P9_15 |   |   |
|   P9_16 |   |   |
|   P9_17 |   |   |
| P9_18   |   |   |
|  P9_19  |   |   |
| P9_20   |   |   |
|   P9_21 |   |   |
|   P9_22 |   |   |
|  P9_23 |   |   |
|  P9_24 |   |   |
|  P9_25 |   |   |
|   P9_26 |   |   |
|   P9_27|   |   |
|  P9_28|   |   |
|  P9_29 |   |   |
|  P9_30 |   |   |
|  P9_31 |   |   |
|  P9_32 |   |   |
|  P9_33 |   |   |
|  P9_34 |   |   |
|  P9_35 |   |   |
|  P9_36 |   |   |
|  P9_37 |   |   |
|  P9_38 |   |   |
|  P9_39 |   |   |
|  P9_40 |   |   |
|  P9_41 |   |   |
|  P9_42|   |   |
|  P9_43|   |   |
|  P9_44 |   |   |
|  P9_45 |   |   |
|  P9_46 |   |   |

Notes

[Design CM4 carrier](https://www.digikey.com/en/maker/projects/creating-a-raspberry-pi-compute-module-4-cm4-carrier-board-in-kicad/7812da347e5e409aa28d59ea2aaea490)

Use [3mm hirose header](https://www.digikey.com/en/products/detail/hirose-electric-co-ltd/DF40HC-3-0-100DS-0-4V-51/4282911) to give 1.5mm for components under the board
