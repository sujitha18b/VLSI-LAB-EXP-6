# VLSI-LAB-EXP-6
# AIM:
To Schematic and Simulate Inverter using CADENCE virtuoso.

# APPARATUS REQUIRED:
CADENCE VIRTUOSO

# PROCEDURE:

# Procedure for Commands to get into Cadence
Right Click and open the terminal window
Type the following commands as follows and press enter.
i) tcsh
ii) source /home/install/cshrc
iii) virtuoso

# Procedure for Schematic simulation using Cadence
Now two windows must open i)virtuoso/command interpreter window ii)”Whats New…"
Close the 2nd window
Use 1st window i.e virtuoso window(CIW) for further processing.
i) Create a New Library
ii) Create Schematic Cell view.
iii) Create the Symbol for schematic Cell view.
iv) Create the test Cell view.
v) Analog simulation by spectre

# Procedure for Creating New Library.
a) File –New – Library
b) Name : Give name for ur library Ex: VLSILAB , Enable Attach to an existing technology library, Click OK
c) Attach the library to the technology library gpdk045.Click OK

# Create Schematic Cell view.
a) Go to 1st window i.e virtuoso(CIW)
b) File-New-Cell view
c) Setup the new file form, Library: Select the one you a created. Cell : Give the experiment name Ex: Inverter View: Schematic
d) Type: Schematic press OK
e) Add the required components from the libraries and make the connections.
f) Go to instance fixed menu or use shortcut key “I” from keypad to go instances Click on browse. This opens the library browser ow select the appropriate library for components like Gpdk045,nmos, pmos
g) Analog library Vdd, Gnd, Vcc, Vpulse, Vsin
h) Make the connections by using fixed narrow wire key
i) Click Check and Save button

# Creating the Symbol for schematic Cell view
a. In the schematic window, execute Crate – Cell view – From Cell view The cell view from cell view window appears Check Lib Name, Cell Name, From View name must be schematic Press ok
b. Now Symbol generation form appears. Click Ok If No changes required
c. A new window with with default symbol is created.
d. Edit the symbol if you want to give actual symbol shape else continue.
i. Execute Create-Cell view-from cell view
ii. Library Name and Cell Name must be same which you have used for schematic. Press OK
iii. Check for the position of pin side.Prss OK
iv. Edit for the shape by Create-Shape-Choose required options to edit.

# Creating the new test cell view
a) Go to CIW window, Execute File-New-Cell view
b) Setup the new file form
Library: Select the one you a created.
Cell: Cell name must be different from the name used in schematic cell view. Ex: Inverter_test
View: Schematic
Type: Schematic press OK
Analog simulation by SPECTRE.
a. In test cell view window
b. Launch – ADE L(Analog Design Environment)
c. Execute Setup—Simulation/directory/Host A new window opens
d. Set the simulation window to spectre and click ok
e. Execute Setup-Model Library. Anew window opens, Check of gpdk.scs as lib and section type as stat then press OK.
f. Execute Analysis – Choose. A window opens.
g. Select the type and set the specifications and press OK
h. Execute Output s—to be plotted – Select on Schematic
i. Then Select the INPUT WIRE(Vin ) and OUTPUT WIRE(Vout) from your test Schematic using mouse
j. Execute Simulation -- Net list and Run

 # Simulation Settings
Setup for transient analysis:

1.Stop time = 400n
Setup for D.C analysis
2.Component to be selected in schematic is for d.c analysis
3.Start = -1 Stop = 1 resp.

# CMOS INVERTER
![image](https://github.com/navaneethans/VLSI-LAB-EXP-6/assets/161813783/c5a07325-e73c-4d58-9740-e2ff18a6a0ff)

![image](https://github.com/navaneethans/VLSI-LAB-EXP-6/assets/161813783/89f6dc69-13be-4d01-9b82-3d40e3572b88)

# OUTPUT
![image](https://github.com/navaneethans/VLSI-LAB-EXP-6/assets/161813783/6d20d1a5-ddc0-48a0-bd2a-54ac8afb97a7)


# NAND GATE
![image](https://github.com/navaneethans/VLSI-LAB-EXP-6/assets/161813783/1e5058cb-f830-4966-85c1-d5d8125438d2)

![image](https://github.com/navaneethans/VLSI-LAB-EXP-6/assets/161813783/d4afc646-298d-4d22-a813-691575c416ab)

# OUTPUT
![image](https://github.com/navaneethans/VLSI-LAB-EXP-6/assets/161813783/2c0b0863-176e-42bc-a40f-87adde362246)

#  NORGATE

![image](https://github.com/navaneethans/VLSI-LAB-EXP-6/assets/161813783/da61e63e-c794-4567-9274-790a758890b6)

![image](https://github.com/navaneethans/VLSI-LAB-EXP-6/assets/161813783/4ad4b082-5fcc-4cf6-a514-e84261f266e0)


# RESULT
 The schematic and simulate inverter using CADENCE is done and verified successfully






