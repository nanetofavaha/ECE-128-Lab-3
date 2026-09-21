This project implements a 4-bit full adder with a seven-segment display on the Basys 3 FPGA board. The design uses a 4-bit ripple-carry adder, a 2:1 multiplexer, and a BCD-to-seven-segment decoder connected through a top module. The design was written and simulated in Verilog using Xilinx Vivado and implemented on the Basys 3 FPGA board.

The project includes:
- BCD-to-seven-segment decoder
- 4-bit ripple-carry adder
- 2:1 multiplexer
- Top module
- Testbench

To simulate the design:
- Open the project in Xilinx Vivado.
- Add the Verilog source files and testbench.
- Run Behavioral Simulation.
- Use the waveform to verify the outputs for the different input cases.

To implement the design on the FPGA:
- Add the Basys 3 constraint file with the appropriate pin assignments.
- Run Synthesis and Implementation.
- Generate the bitstream.
- Connect the Basys 3 board and program it using Hardware Manager.
- Use the assigned switches as inputs and observe the output on the seven-segment display.
