# slowDownForSmallLoops
Detect perimeters/dense support layers and adjust speeds of smaller outline/loops in a G-Code file

usage: smallLoops.py filename slowDownSpeed LengthThreshold

example smallLoops.py darthRevanMask.gcode 360 30

# Requirements
filename must contain .gcode

slowdownspeed must be a positive interger

LengthThreshold must be positive

# To enable dense support slow downs
Change denseSupportToggle = 0 to denseSupportToggle = 1 and save the script before running it.
