# Open-Source-ROBAIR
A new open source version of the ROBAIR project originally designed by Jérôme Maisonnasse

# Welcome to the RobAir Open source project!

If you read this, then you probably show some interest in our project Robair. In this guide, we are going to show you the method we used to build our very own Robair. This project is still a prototype, so obviously the method we chose is not perfect and can be improved. Feel free to do your own changes and share with us your upgrades! Just keep in mind that the following guide is just an example of how you can build Robair, and you can change it if you have a better way of doing it.
 
Required material : screws, Plexiglas
Required components: Hoverboard, battery charger, pole, idler wheel (x2), nuts, screws, washers
Required machines : laser cutting machine using CorelDraw,  3D Printer using Repetier Host, Stratoconception using StratoConcept, saw, folding machine, rulers, screwdriver, file
 
# 1 How to build a Robair similar to our :

# Step 1: machining of the pieces thanks to the laser cutting machine 
       
  Get the .dxf files provided on Github [DFX FILES](https://github.com/cinatalia/Open-Source-ROBAIR/tree/master/DFX)
      
  Open CorelDraw
      
  Import the files that you wish to cut (be careful to the dimensions of the plate and the thickness of the parts)
      
  Choose the option “very fine outlines” and “connect the curvatures”
      
  Print the file after selecting the adapted parameters for the plate thickness
       
  Place the plate on the correct position and initialize the origin
      
  Activate the ventilation
      
  Launch the program
 
# Step 2: machining of the pieces thanks to the 3D Printer:
      
  Get the .stl files provided on Github [STL FILES](https://github.com/cinatalia/Open-Source-ROBAIR/tree/master/STL)
  
  Open Repetier Host          
 
# Step 3 : machining of the pieces thanks to StratoConception : 
       
  Get the .stl files provided on GitHub [STL FILES](https://github.com/cinatalia/Open-Source-ROBAIR/tree/master/STL)
  
  Open StratoPro
 
  Choose the correct thickness and positioning of the slices according to the thickness of the available plates
 
  Define the positioning of the inserts (metal rods used to maintain the alignment when we glue the differents slices together
  
  Choose the correct tool for the cutting
  
  Check that the tool path matches the geometry of the parts
 
  Create the machine code and put it into the tower 

# Step 4: folding the pieces : 

As you may have noticed, some pieces have been folded to simplify the building of our Robair. 

To fold the pieces, start by cutting the pattern file with the laser cutting machine. Then, simply draw a line where you went to bend the part and using the folding machine, heat the line until it’s limp enough to be folded at the correct angle

# Step 5 : Assembly and mounting of Robair :

   Now that you have all the components of Robair, you can start the assembly.


# II) How to build a different Robair : 

In case you want to change the structure of the robot and add your own upgrades, you only have to follow these steps :

get the CAD files provided on GitHub. The files are available in different formats (.PRT ,.STEP, .IGES),[PRT FILES](https://github.com/cinatalia/Open-Source-ROBAIR/tree/master/Original%20version%20Creo%20.PRT), [STEP FILES](https://github.com/cinatalia/Open-Source-ROBAIR/tree/master/STEP), [IGES FILES](https://github.com/cinatalia/Open-Source-ROBAIR/tree/master/IGES)

If you use Creo, SolidWorks or Catia, the .prt and .step files will do just fine. However, if you want to use a free open source CAD software like FreeCAD, know that the .iges format is pretty standard and should work on any software you use
change the design of the CAD  go back to part I and follow the steps. 
