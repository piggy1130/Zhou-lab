# Zhou-lab  

## Install Python packages  
py -m pip install numpy  

## Access to the Database  
window: ${\textsf{\color{blue}\\\\zhoulab-nas-1}}$  

example:  
import os  
filename = r'\\\\zhoulab-nas-1\Data\jl_text.txt'  
fileObject = open(filename, "a")  
fileObject.write("Hello World")  

