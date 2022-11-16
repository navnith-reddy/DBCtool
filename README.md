# Device Boundary Tool

Calculating the Device Boundary Critera can be a unecessarily tedious task so in this project, the possibility of automating the process is explored.

The DBC Tool project heavily utilises the pycraf library which contains spectrum management functions.

## WORK IN PROGRESS

1. Pycraf Path Attenuation Parameters
    - Review Pycraf notebooks on path attenution
    - Record significant parameters and determine default values

2. Convert total_atten array into geodataframe
    - Apply DBC limit value to array
    - Convert array into geodataframe

3. Create a single polygon
    - Filter out geodataframe points outside of limit value
    - Perform unary union on geodataframe
    - Export as polygon as shapefile