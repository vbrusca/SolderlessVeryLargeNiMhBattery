# SolderlessVeryLargeNiMhBattery
A free, open source, repository with 3D printable models for creating safe, large, DIY, batteries that require no soldering.
<br>
<br>

**WARNING: Do not make the mistake of viewing these battery packs as innocuous. It's very easy to dismiss AA or AAA batteries as something inherently safe. I accidentally shorted one of these
packs for a ms and it vaporized the metal lead and shot a spark a few feet across the room. Now if it was a Li-Ion battery it would probably have exploded at that point. Simply put, make sure there is no metal
in your build area and make sure all the metal involved with your voltmeter/equipment, is wrapped in protective plastic wrap.
<br>
<br>

# Authors
Carlo Bruscani
<br>
Victor G. Brusca
<br>

# Update
Addition of a new NiMh very large battery creation technique using high temp resistant silicon tubing and 3D printed end caps. This results in a much faster battery build at a slightly higher cost per cell.

# Very Large NiMh Battery Technique: Silicon Tubing and 3D Printed Caps
This design has many benefits including the following:<br>
<ul>
  <li>No soldering required: Increase safety as there are less metals around the workspace to cause a short. Scaffolding adds negligible weight to the battery bank. Known ampacity using tried and true wire guages as opposed to sheets of metal with less known ampacities.</li>
  <li>Easily scales up: The batteries can be easily altered in ampacity and voltage using the base 6V 2.5Ah cell.</li>
  <li>NiMh chemistry: NiMh chemistry is non toxic, readily available, less reactive, easier to manage. No thermal runaway!</li>
</ul>

Known Issues:<br>
<ul>
  <li>
  Potential cooling issues. It is unknow how easily heat can move through the silicon tubing.
  </li>
</ul>

To offset the known issue I built a very large battery and set a specific max wattage usage so that the draw on each cell is negligible and there is no real heat generation from the cells.

# Creation Steps

## Step 1
Get the basic supplies needed to build the base 6V 2.5Ah cell.
<br>

<ul>
  <li>1. Heat resistent silicon tubing ID: 16mm, OD: 20mm</li>
  <li>2. 12 or 14 AWG pure copper stranded wire for connecting the base cells</li>
  <li>3. Two 3D printed end caps, nimh_tube_batt_cap_1_D_1.stl.</li>
  <li>4. 5 NiMh rechargable 2500mAh batteries per 6V 2.5Ah cell, 20 for a 6V 10Ah cell.</li>
  <li>5. Thin zip tie about 5 to 8 inches long.</li>
</ul>

![alt text](https://github.com/vbrusca/SolderlessVeryLargeNiMhBattery/blob/main/images/nimh_tube_batt/pic1_basic_supplies.jpg?raw=true)
<br>

## Step 2
Cut the silicon tube to about 10.75 inches. Fill the tube with 5 NiMh rechargable AA batteries in series for 6V. To make a 12V cell do this twice.

![alt text](https://github.com/vbrusca/SolderlessVeryLargeNiMhBattery/blob/main/images/nimh_tube_batt/pic2_silicon_tube_16mmID_20mmOD_10_nimh_batt.jpg?raw=true)
<br>

## Step 3
Prepare the wired caps with the wire curled inside for the positive terminal and the wired curled around the edge of the cap for the negative terminal.
<br>

![alt text](https://github.com/vbrusca/SolderlessVeryLargeNiMhBattery/blob/main/images/nimh_tube_batt/pic3_wired_caps_for_joining_cells.jpg?raw=true)
<br>

## Step 4
Use the zip tie to secure the cap to the end of the tube. Make sure to use the cap setup for the negative terminal on the negative terminal and positve on positive. If the cap slips after completing the other end use a second zip tie to secure it further.
<br>

![alt text](https://github.com/vbrusca/SolderlessVeryLargeNiMhBattery/blob/main/images/nimh_tube_batt/pic4_use_of_zip_ties.jpg?raw=true)
<br>

## Step 5
Complete one 6V 2.5Ah cell.
<br>

![alt text](https://github.com/vbrusca/SolderlessVeryLargeNiMhBattery/blob/main/images/nimh_tube_batt/pic5_one_complete_cell.jpg?raw=true)
<br>

![alt text](https://github.com/vbrusca/SolderlessVeryLargeNiMhBattery/blob/main/images/nimh_tube_batt/pic6_close_up_of_end.jpg?raw=true)
<br>

![alt text](https://github.com/vbrusca/SolderlessVeryLargeNiMhBattery/blob/main/images/nimh_tube_batt/pic7_voltage_of_one_cell.jpg?raw=true)
<br>

## Step 6
Join 2 cells into one 12v 2.5Ah cell.
<br>

![alt text](https://github.com/vbrusca/SolderlessVeryLargeNiMhBattery/blob/main/images/nimh_tube_batt/pic8_voltage_after_joining.jpg?raw=true)
<br>

## Conclusion
You can easily build very large NiMh batteries this way. Like this nominally 720Wh 12V, 60AH battery.
<br>

![alt text](https://github.com/vbrusca/SolderlessVeryLargeNiMhBattery/blob/main/images/nimh_tube_batt/pic9_720WH_nominal_with_300W_inverter_and_solar_charger.jpg?raw=true)
<br>

![alt text](https://github.com/vbrusca/SolderlessVeryLargeNiMhBattery/blob/main/images/nimh_tube_batt/pic10_case_with_voltage_display.jpg?raw=true)
<br>

This particular setup can be charged with a 10A solar charge controller and 100W panel. You could probably go up to 200W or 250W if you designed your wiring for it. It can power a 300W inverter easily but I would max usage to 200W unless you have specifically wired things to handle 300W, which would draw 25 amps from the battery. It also supports a direct 12V to USB converter for easily powering up USB devices without having to use the inverter.
<br>

So far using it daily for a few weeks it handles any charge controler I've thrown at it that can working with 12V Lifeo4 or lead acid batteries. It seems to hold a max voltage of 13.7 with a theoretical maximum of 14V. But it can handle a charge voltage up to 14.6V, or so I have read.
<br>

You can also slow charge it with an NiMh AC charger that supports up to 10 cells in series.
Although at low current this approach will take a long time to charge the battery. For this purpose there is an XT60 plug wired into the connector bar as well as a voltage display.
<br>

Enjoy!! Go, build some big batteris and power stuff.


# Very Large NiMh Battery Technique: 3D Printed Scaffolding
This design has many benefits including the following:<br>
<ul>
  <li>No soldering required: Increase safety as there are less metals around the workspace to cause a short. Lighter overall weight due to plastic scaffolding. Known ampacity using tried and true wire guages as opposed to sheets of metal with less known ampacities.</li>
  <li>Easily scales up: The batteries can be connected in 3 dimensions so you can easily build a battery pack of great capacity while keeping everything connected.</li>
  <li>NiMh chemistry: NiMh chemistry is non toxic, readily available, less reactive, easier to manage. No thermal runaway!</li>
  <li>Passively Cooled: The battery pack as designed, is perfectly suited at passive cooling with lots of space for air movement at the cost of density and overall size.</li>
</ul>

# Example
The following image demonstrates using the AAA connector and cap models to create a 60V (nominal), 60Wh battery pack, out of 50 AAA batteries in series.
<br>

![alt text](https://github.com/vbrusca/SolderlessVeryLargeNiMhBattery/blob/main/images/large_aaa_nimh_batt_sm.jpg?raw=true)
<br>

The models have been posted for both AAA and AA cells. You'll have to run some test prints to get the right settings for your printer.
Here are some sample battery packs built using this approach.
<br>

600Wh at 60V using 200 AA NiMh rechargeable batteries:
<br>
![alt text](https://github.com/vbrusca/SolderlessVeryLargeNiMhBattery/blob/main/images/nimh_aa_600Wh_at_60V.jpg?raw=true)
<br>

360Wh at 60V using 300 AAA NiMh rechargeable batteries:
<br>
![alt text](https://github.com/vbrusca/SolderlessVeryLargeNiMhBattery/blob/main/images/nimh_aaa_360Wh_at_60V.jpg?raw=true)
<br>

A look at the caps up close. The caps are slotted to aid in the alignment of the zip tie. The zip tie is used to keep a row, in this case 6 NiMh batteries in series, connected together,
and connected to the next row. I recommend using two leads at the terminals of the battery pack. One of which that is not connected to the larger battery structure. This allows you to run checks and tests against each "cell" in the larger pack. It is recommended to use color coded caps that match the polarity of the battery terminal it connects to.
<br>
![alt text](https://github.com/vbrusca/SolderlessVeryLargeNiMhBattery/blob/main/images/nimh_caps_up_close.jpg?raw=true)
<br>

Build some super large NiMh batteries and see what you can power with them. Free up valuable Li-Ion resources by using NiMh where NiMh does well/better than Li-Ion.
Enjoy!!
