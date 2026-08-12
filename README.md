# Assembly course

Eleven labs, from a first DOS program to disassembling a protected binary. The early ones
target 16-bit real mode and talk to the machine through DOS interrupts, the later ones move
to 32-bit Windows and to assembly called from C++.

| Lab | Topic |
|-----|-------|
| [lab_01](lab_01) | Printing a string through `INT 21h` |
| [lab_02](lab_02) | Segments, stack and message output |
| [lab_03](lab_03) | A multi-module program, data exchange between segments |
| [lab_04](lab_04) | A 9×9 matrix with dynamic memory allocation |
| [lab_05](lab_05) | Menu-driven 16-bit input, output in several number systems, a table of subroutine pointers |
| [lab_06](lab_06) | A resident program hooking `INT 08h` and changing the key repeat rate through port 60h |
| [lab_07](lab_07) | `strcpy` written in assembly and called from C++ |
| [lab_08](lab_08) | `sin(x)` on the x87 FPU, integrated with C++ |
| [lab_09](lab_09) | Assembly against C++ over 10⁷ iterations, with timing |
| [lab_10](lab_10) | A windowed MASM32 application on WinAPI |
| [lab_11](lab_11) | Reverse engineering a protected `crackme.exe`, 29 procedures, PE analysis |
