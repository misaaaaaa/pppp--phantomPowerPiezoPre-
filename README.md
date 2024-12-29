# Piezo preamp

Clon del proyecto de [DJJules](https://www.instructables.com/Hi-Z-Opamp-Piezo-Buffer/), que aprovecha los +48V del phantom power para alimentar el preamplificador de un micrófono piezoeléctrico. El componente principal del circuito es el amplificador operacional OPA1642, que por su bajo consumo de corriente es ideal para esta aplicación.

## Esquemático

![Esquemático!](/sch.png "Esquemático")

## PCB Layout

![pcb!](/layout.png "pcb")


## Lista de Materiales

| Qty | Reference(s)                                       | Value   | LibPart                | Footprint                             |
|-----|----------------------------------------------------|---------|------------------------|---------------------------------------|
| 1   | R2                                                 | 1M      | Resistencia            | Resistencia 1/4W                      |
| 4   | R3*, R4, R7, R11                                    | 2k2     | Resistencia            | Resistencia 1/4W                      |
| 2   | R5, R6                                             | 47k     | Resistencia            | Resistencia 1/4W                      |
| 1   | R8                                                 | 200R    | Resistencia            | Resistencia 1/4W                      |
| 2   | R9, R10                                            | 47R     | Resistencia            | Resistencia 1/4W                      |
| 2   | C4, C8                                             | 100n    | Condensador            | 3.2 mm ancho (mínimo 50v)             |
| 5   | C1, C3, C5, C6, C7                                 | 22u     | Condensador polarizado | 5mm diametro 2.5mm pitch (mínimo 50v) |
| 1   | D1                                                 | 12v     | Diodo Zener            | DO-35                                 |
| 8   | GND_1, GND_2, SIG1, VCC_1, VCC_2, XLR1, XLR2, XLR3 | PAD1    | Conector para soldar   |                                       |
| 2   | H1, H2                                             | M3      | Mounting Hole          | Perno M3 o separador de placas        |
| 1   | U1                                                 | OPA1642 | Op amp                 | SOIC-8 Package                        |

Nota: En la primera versión de la pcb (morada), la serigrafía "R3" se encuentra escondida debajo del IC, por lo que no es fácil de encontrar su ubicación. La resistencia va instalada justo al lado de "C3".

## Imagen de referencia

![foto!](/foto.png "foto")