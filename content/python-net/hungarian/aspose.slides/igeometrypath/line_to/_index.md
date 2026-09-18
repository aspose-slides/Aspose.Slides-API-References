---
title: line_to method
second_title: Aspose.Slides Pythonhoz a .NET-en keresztül API referencia
description: 
type: docs
url: /hu/aspose.slides/igeometrypath/line_to/
weight: 40
---
## line_to(self, point) {#asposepydrawingpointf}
Vonal hozzáadása az útvonal végéhez


```python
def line_to(self, point):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| point | **aspose.slides.PointF** | A vonal végpontja |


## line_to(self, x, y) {#float-float}
Vonal hozzáadása az útvonal végéhez


```python
def line_to(self, x, y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | A vonal végpontjának X koordinátája |
| y | **float** | A vonal végpontjának Y koordinátája |


## line_to(self, point, index) {#asposepydrawingpointf-int}
Vonal hozzáadása az útvonal megadott helyére


```python
def line_to(self, point, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| point | **aspose.slides.PointF** | Végpont |
| index | **int** | A szegmens indexe a PathData-ban |

### Kivételek

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | A szegmens index a PathData tartományán kívül van |


## line_to(self, x, y, index) {#float-float-int}
Vonal hozzáadása az útvonal megadott helyére


```python
def line_to(self, x, y, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | A pont X koordinátája |
| y | **float** | A pont Y koordinátája |
| index | **int** | A szegmens indexe a PathData-ban |

### Kivételek

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | A szegmens index a PathData tartományán kívül van |



### Lásd még
* class [`IGeometryPath`](/slides/python-net/hu/aspose.slides/igeometrypath)
* module [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)