The RV32I Processor is designed to support all RV32I Base Integer Instructions (Total -39).
It’s a three-stage pipelined processor that executes 32-bit instructions in program order.
@Responsibilities for Design:
Synthesizing the RISC-V RTL and generating the Gate Level netlist.
>Implementing floor planning, Placement, and Routing processes on the netlist.
>Implementing Clock Tree Synthesis
>Performing Timing Analysis and achieving timing closure.
>Perform DRC and LVS for signoff
>Exporting the final GDS-II
>all the above steps are done using Design compile(DC)-for synthesis and ICC2-for floorplan to routing
and all the command are given in  the pdf 
