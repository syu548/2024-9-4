# 1주차 Hello World 실습
import pylab as py

x_deg = py.arange(-180, 180+1)
x_rad = py.deg2rad(x_deg)
y = py.sin(x_rad)

py.plot(x_deg, y)

py.xlabel('x(deg)')
py.ylabel('sin(x)')
py.grid(True)
 
 
|주차|실습|
|:-----:|:-----:|
|1 | Hello World| 
|2| Github Classroom|
 
