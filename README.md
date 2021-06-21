# Wasteboard template for the Wegstr CNC machine

This is a KiCad project for building a perfect wasteboard for the Wegstr CNC machine.

Here is a preview of the template:

![image](https://user-images.githubusercontent.com/820984/121825921-e75a0180-cc69-11eb-842d-b607f34cf5ca.png)

Here is an example wasteboard produced with this template:

![image](https://user-images.githubusercontent.com/820984/121826411-5b95a480-cc6c-11eb-905b-65e3aeb3ab73.png)

## How to Build a Wasteboard

1. Print the template on US Letter paper.  [A PDF render of the PCB is provided for convenience](https://raw.githubusercontent.com/synthead/wegstr-wasteboard/master/wegstr-wasteboard.pdf).
1. Cut a piece of scrap wood to the dimensions of the edge cuts in the template.
1. Tape the template onto the wasteboard using painter's tape (or something with similar adhesion).
1. Drill holes in the center of the circular edge cuts with a 3/16" drill bit.
1. Remove the template from the wasteboard.

## How to Use the Wasteboard

The wasteboard will have loose tolerances, and will move slightly until it is tighened to the CNC bed.  When tightening tapered screws to wood, it will impress a tapered shape into the wood and keep the wood from moving on the CNC bed when in use.

It is important to ensure that the wasteboard is fastened to the CNC bed before fastening a board.  If a board is fastened first, wasteboard might reposition itself slightly when it is tightened afterwards, and the board might loosen from the wasteboard.

1. Loosely thread tapered screws directly through the wasteboard to the CNC bed.  Do not tighten.
1. Loosely thread tapered screws with hardware that will hold a board to the wasteboard.  Do not tighten.
1. Gently tighten the wasteboard to the CNC bed.
1. Gently tighten the board to the wasteboard.

## Notes

- The screws for the wasteboard are M4-0.7 in size.  The included screws are 25 mm in length.
- The CNC bed is 1.5 cm tall, and screws should not protrude through the bottom of the bed because they may obstruct the mechanics underneath.
- There is approximately 61 mm of height between the CNC bed and the tool collet at the highest Z position.  With most CNC tools being about 38 mm in height, the wasteboard thickness should not exceed 20 mm.  At 20 mm, there will be only about a 3 mm maximum gap to change tools.
