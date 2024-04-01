# FULL_ADDER
# AIM:

To simulate and synthesis full adder using vivado 2023.2

# APPARATUS REQUIRED:

vivado 2023

# PROCEDURE:
```
STEP:1 Start the vivado software, Select and Name the New project.
STEP:2 Select the device family, device, package and speed.
STEP:3 Select new source in the New Project and select Verilog Module as the Source type.
STEP:4 Type the File Name and module name and Click Next and then finish button. Type the code and save it.
STEP:5 Select the run simulation and then run Behavioral Simulation in the Source Window and click the check syntax.
STEP:6 Click the simulation to simulate the program and give the inputs and verify the outputs as per the truth table.
STEP:7 compare the output with truth table.
```
# Truth Table
![image](https://github.com/RESMIRNAIR/FULL_ADDER/assets/154305926/02ead8f5-d958-4c89-ac51-368ca086cf41)
# Circuit Diagram
![image](https://github.com/RESMIRNAIR/FULL_ADDER/assets/154305926/418e00aa-ed19-4ab3-a413-bae9575bff0e)
![image](https://github.com/RESMIRNAIR/FULL_ADDER/assets/154305926/0c26fe47-d78c-43dd-ac0d-804e427a3bbc)
# Verilog code module
```
FA(a,b,cin,sum,cout);
input a,b,cin;
output sum,cout
wire w1,w2,w3;
xor g1(w1,a,b);
and g2(w2,w1,cin);
and g3(w3,a,b);
xor g4(sum,w1,cin);
or g5(cout,w2,w3);
endmodule
```
# output
![318186318-4fad8fc6-3ce6-4168-8ec8-e66fd92dfdae](https://github.com/vishalmagesh/FULL_ADDER/assets/160302888/f3b28590-cffc-4660-b801-b76c9fd30ebf)
# result

Thus the simulatation and synthesis of full adder using vivado was successfully executed and verified.
