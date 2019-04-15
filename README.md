# Awesome RISC-V Core List [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of spec, maturity comparison between current Open RISC-V cores. Current online lists and repos don't include the Performance, Power, Area (PPA) information, which is a very important information for developing embedded systems.

## Table of Contents

- [PPA Comparison](#PPA)
- [Cores](#core)
  - [Industry](#industry)
  - [Academia](#academia)

## PPA Comparison
Project Name | Chip Name | Clock Rate (MHz) | Size (um^2) | Tech Node (nm) | Power | Gates | Link
---- | ----- | ---------- | --------- | ------- | -------- | -------- | -------
PULP | Arnold | 330 | 3000 x 3000 | 22 | NA | NA | [Link](http://asic.ethz.ch/2018/Arnold.html)
PULP | Kosmodrom | 1300 | 3000 x 3000 | 22 | 1 pW (@1.8V, 1MHz) | 20 MGe | [Link](http://asic.ethz.ch/2018/Kosmodrom.html)
PULP | Poseidon | 700 | 3000 x 3000 | 22 | 30 mW (@0.8V, 700MHz) | NA | [Link](http://asic.ethz.ch/2018/Poseidon.html)
PULP | Pulp v1 | 475 | 1650 x 1650 | 28 | 8 mW (@0.7V, 10MHz) | 700 kGe | [Link](http://asic.ethz.ch/2013/Pulp.html)
PULP | Pulp v2 | 1000 | 1650 x 1650 | 28 | 100 mW | 1800 kGe | [Link](http://asic.ethz.ch/2014/Pulpv2.html)
PULP | Pulp v3 | 66 | 1650 x 1650 | 28 | 1.2 mW (@0.6V, 50MHz) | 2500 kGe | [Link](http://asic.ethz.ch/2015/Pulpv3.html)
PULP | Honey_Bunny | 60 | 1500 x 2000 | 28 | 1 mW (@1.2V, 1MHz) | 2 MGe | [Link](http://asic.ethz.ch/2015/Honey_Bunny.html)
PULP | Mr.Wolf | 450 | 3200 x 3200 | 40 | 154 mW (1.1V, 450MHz) | 1800 kGe | [Link](http://asic.ethz.ch/2017/Mr.Wolf.html)
PULP | Mia_Wallance | 400 | 3950 x 1875 | 65 | 1 mW (@1.2V, 1MHz) |2 Mge | [Link](http://asic.ethz.ch/2015/Mia_Wallace.html)
PULP | Fulmine | 400 | 2626 x 2626 | 65 | 13 mW (@0.8V, 104MHz) | 2500 kGe | [Link](http://asic.ethz.ch/2015/Fulmine.html)
PULP | Artemis | 500 | 1252 x 1252 | 65 | 1mW (@1.2V, 1MHz) | 600 Kge | [Link](http://asic.ethz.ch/2014/Artemis.html)
PULP | Hecate | 500 | 1252 x 1252 | 65 |1mW (@1.2V, 1MHz) | 600 Kge | [Link](http://asic.ethz.ch/2014/Hecate.html)
PULP | Selene | 500 | 1252 x 1252 | 65 | 1mW (@1.2V, 1MHz) | 600 Kge | [Link](http://asic.ethz.ch/2014/Selene.html)
PULP | Diana | 500 | 1252 x 1252 | 65 | 1mW (@1.2V, 1MHz) | 600 Kge | [Link](http://asic.ethz.ch/2014/Diana.html)
PULP | Phoebe | 500 | 1252 x 1252 | 65 | 22mW (@1.2V, 100MHz) | 600 Kge | [Link](http://asic.ethz.ch/2015/Phoebe.html)
PULP | Imperio | 650 | 1252 x 1252 | 65 | 32.8 mW (1.2V, 400MHz) | 500 kGe | [Link](http://asic.ethz.ch/2015/Imperio.html)
PULP | Patronus | 100 | 2626 x 2626 | 65 | 999 mW (1.2V, 400MHz) | 5 Mge | [Link](http://asic.ethz.ch/2016/Patronus.html)
PULP | Scarabaeus | 200 | 2626 x 1252 | 65 | 45.97 mW (1.2, 200MHz) | 1200 kGe | [Link](http://asic.ethz.ch/2018/Scarabaeus.html)
PULP | Atomario | 200 | 2626 x 2626 | 65 | 54 mW (1.2V, 200MHz) | 3 Mge | [Link](http://asic.ethz.ch/2018/Atomario.html)
PULP | Vivosoc | 140 | 4000 x 3200 | 130 | 45 mW (1.2V, 40MHz) | 600 kGe | [Link](http://asic.ethz.ch/2015/Vivosoc.html)
PULP | Vivosoc2 | 64 | 4368 x 4768 | 130 | 20 mW (@50MHz, 1.2V) | 800 Kge | [Link](http://asic.ethz.ch/2016/Vivosoc2.html)
PULP | Vivosoc2.001 | 64 | 4368 x 4768 | 130 | 20mW (50MHz, 1.2V) | 800 Kge | [Link](http://asic.ethz.ch/2016/Vivosoc2.001.html)
PULP | Vivosoc3 | 100 | 4368 x 4768 | 110 | 10mW ( 50MHz, 0.8V) | 2MGe | [Link](http://asic.ethz.ch/2018/Vivosoc3.html)
PULP | Triphos | 16 | 3000 x 4000	 | 130 | 999mW (0.1V, 1MHz) | 500 kGe | [Link](http://asic.ethz.ch/2016/Triphos.html)
PULP | Or10n | 360 | 1525 x 1525 | 180 | 1mW (@1.8V, 1MHz) | 80kGe | [Link](http://asic.ethz.ch/2013/Or10n.html)
PULP | Sir10us | 166 | 1525 x 1525 | 180 | 93 mW(@1.8V, 166MHz) | 100 kGe | [Link](http://asic.ethz.ch/2013/Sir10us.html)
PULP | Sid | 15 | 7201 x 8160 | 180 | 3W (1.0V, 15MHz) | 2MGe | [Link](http://asic.ethz.ch/2015/Sid.html)
PULP | Diego | 15 | 7201 x 8160 | 180 | 3W (0.8V, 15MHz) | 2MGe | [Link](http://asic.ethz.ch/2015/Diego.html)
PULP | Manny | 1.25 | 7201 x 8160 | 180 | 3W (0.6V, 1.5MHz) | 2MGe | [Link](http://asic.ethz.ch/2015/Manny.html)

## Cores
### Industry
Name | Links | Priv. spec | User spec | License | Supplier
---- | ----- | ---------- | --------- | ------- | --------
rocket | [GitHub](https://github.com/freechipsproject/rocket-chip) | 1.11-draft | 2.3-draft | BSD | SiFive, UCB Bar
freedom | [GitHub](https://github.com/sifive/freedom) | 1.11-draft | 2.3-draft | BSD | SiFive
Berkeley Out-of-Order Machine (BOOM) | [GitHub](https://github.com/ucb-bar/riscv-boom) | 1.11-draft | 2.3-draft | BSD | Esperanto, UCB Bar
ORCA | [GitHub](https://github.com/vectorblox/orca) |  | RV32IM | BSD | VectorBlox
Minerva | [GitHub](https://github.com/lambdaconcept/minerva) | 1.10 | RV32I | BSD | LambdaConcept
OPenV/mriscv | [GitHub](https://github.com/onchipuis/mriscv) |  | RV32I(?) | MIT | OnChipUIS
VexRiscv | [GitHub](https://github.com/SpinalHDL/VexRiscv) |  | RV32I[M][C] | MIT | SpinalHDL
Roa Logic RV12 | [GitHub](https://github.com/roalogic/RV12) | 1.9.1 | 2.1 | Non-Commercial License | Roa Logic
SCR1 | [GitHub]( https://github.com/syntacore/scr1) | 1.10 | 2.2, RV32I/E[MC] | Solderpad Hardware License v. 0.51 | Syntacore
Hummingbird E200 | [GitHub](https://github.com/SI-RISCV/e200_opensource) | 1.10 | 2.2, RV32IMAC | Apache 2.0 | Bob Hu
Shakti | [Website](http://shakti.org.in/),[GitLab](https://gitlab.com/shaktiproject) | 1.11 | 2.2, RV64IMAFDC | BSD | IIT Madras
ReonV | [GitHub](https://github.com/lcbcFoo/ReonV) |  |  | GPL v3 |
PicoRV32 | [GitHub](https://github.com/cliffordwolf/picorv32) | | RV32I/E[MC] | ISC | Clifford Wolf
MR1 | [GitHub](https://github.com/tomverbeure/mr1) | | RV32I | Unlicense | Tom Verbeure
SERV | [GitHub](https://github.com/olofk/serv) | | RV32I | ISC | Olof Kindgren
SweRV EH1 | [GitHub](https://github.com/westerndigitalcorporation/swerv_eh1) | | RV32IMC | Apache 2.0 | Western Digital Corporation
Reve-R | [GitHub](https://github.com/atthecodeface/cdl_hardware) | 1.10 | RV32IMAC | Apache 2.0 | Gavin Stark

### Academia
Name | Links | Priv. spec | User spec | License | Supplier
---- | ----- | ---------- | --------- | ------- | --------
RI5CY | [GitHub](https://github.com/pulp-platform/riscv) |  | RV32IMC | Solderpad Hardware License v. 0.51 | ETH Zurich, Università di Bologna
Zero-riscy | [GitHub](https://github.com/pulp-platform/zero-riscy) |  | RV32IMC | Solderpad Hardware License v. 0.51 | ETH Zurich, Università di Bologna
Ariane | [Website](https://pulp-platform.github.io/ariane/docs/home/),[GitHub](https://github.com/pulp-platform/ariane) |  | RV64IMC | Solderpad Hardware License v. 0.51 | ETH Zurich, Università di Bologna
Riscy Processors | [Website](http://csg.csail.mit.edu/riscy-e/),[GitHub](https://github.com/csail-csg/riscy) |  | | MIT | MIT CSAIL CSG


## Contributing
<p align="center">
  <img src="http://cdn1.sportngin.com/attachments/news_article/7269/5172/needyou_small.jpg" alt="We Need You!">
</p>

Please help contribute this list by contacting [me](https://jasonlo0509.github.io/) or add [pull request](https://github.com/jasonlo0509/awesome-processing-in-memory/pulls)

Markdown format:
```markdown
- Paper Name [[pdf]](link) [[code]](link)
  - Author 1, Author 2, Author 3. *Conference'Year*
```


## License

[![PDM](https://licensebuttons.net/p/mark/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Yun-Chen Lo (yclo)](https://jasonlo0509.github.io/) has waived all copyright and related or neighboring rights to this work.
