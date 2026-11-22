# EX No.4.1. CUT SECTION OF SOLIDS
## DATE:

## AIM
To create the solid model from given drawing and section the solid model

## REQUIREMENTS: 
1. Autodesk fusion 360
2. Windows 10
3.16 GB of RAM (integrated graphics recommend 1 GB or more)
4. 2.5 Mbps or faster download; 500 Kbps or faster upload 

## PROCEDURE:
1. Create a New Design
Open Autodesk Fusion 360, create a new design, and set the units to match the reference drawing.
<img width="237" height="482" alt="Screenshot 2026-11-13 210155" src="https://github.com/user-attachments/assets/25543ccc-5d13-4139-b796-92b6cfb362a1" />

2. Create the Base Plate
Start a sketch on the XY plane.
Draw an obround profile: two rounded ends joined by straight, parallel sides.
Dimension its overall length and width according to the drawing.
Finish the sketch and use Extrude to create the plate thickness.

3. Add the Mounting Holes
Select the top face of the base plate and start a sketch.
Draw a circle near the center of each rounded end, positioned and dimensioned to match the drawing.
Use Extrude > Cut with Through All to create the holes.

4. Create the Cylindrical Boss
Start a sketch on the top face of the plate.
Draw a circle centered between the mounting holes and dimension it to the boss’s outside diameter.
Extrude the circle to the specified height, with the operation set to Join.

5. Create the Stepped Center Bore
On the top face of the boss, sketch the larger bore circle and cut it to the depth shown in the drawing.
Sketch a smaller, concentric circle and cut it through the remaining boss to create the central opening.
Use the drawing dimensions for both bore diameters and depths.

6. Add the Radial Hole
Create a sketching plane at the side of the boss where the radial hole is shown.
Draw and position the hole using the drawing’s diameter and height dimensions.
Cut inward until the hole meets the center bore.
<img width="311" height="417" alt="Screenshot 2026-11-13 210611" src="https://github.com/user-attachments/assets/3717d4a2-b849-4cd3-98da-5a5baba93505" />

7. Finish and Check the Model
Add any fillets or chamfers shown in the drawing. Check the model from the top, side, and isometric views, then save the design with an appropriate project name.
<img width="364" height="173" alt="Screenshot 2026-11-09 171520" src="https://github.com/user-attachments/assets/025b9fe8-3904-4fc9-a4df-4b845906e0bb" />

## INPUT:
![image](https://user-images.githubusercontent.com/113594316/198825351-b514a4e7-06af-4ee0-8197-e8267749f8a8.png)

## OUTPUT:
<img width="988" height="708" alt="Screenshot 2026-11-22 125526" src="https://github.com/user-attachments/assets/081502c0-5e6e-4fd5-9d48-6b6006172cee" />

## RESULT:

Thus, the cut section for solid model is created.

