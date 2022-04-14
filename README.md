# montocarlo-ol-circlearea

A library for Area calculator of overlapped region between 2 Circle using MontoCarlo method (Random Points)

### Installation
```
pip install montocarlo-ol-circlearea
```

### Get started
How to calculate area of overlapped region of the circle with this lib:

```Python
from montocarlo_ol_circlearea import Overlapped_2_circles

# Instantiate a  Overlapped_2_circle object with 3 params c1 ,c2, Random points
MonteCarlo = Overlapped_2_circles([0,0,2],[2,2,2],10000)

# Call the area method
result = MonteCarlo.area()
```
