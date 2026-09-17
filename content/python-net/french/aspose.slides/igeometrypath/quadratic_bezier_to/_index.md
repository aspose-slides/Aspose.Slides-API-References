---
title: quadratic_bezier_to method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/igeometrypath/quadratic_bezier_to/
weight: 60
---
## quadratic_bezier_to(self, point1, point2) {#asposepydrawingpointf-asposepydrawingpointf}
Ajoute une courbe de Bézier quadratique à la fin du chemin


```python
def quadratic_bezier_to(self, point1, point2):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Direction point |
| point2 | **aspose.slides.PointF** | End point |


## quadratic_bezier_to(self, point1, point2, index) {#asposepydrawingpointf-asposepydrawingpointf-int}
Ajoute une courbe de Bézier quadratique à l'emplacement spécifié du chemin


```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Direction point |
| point2 | **aspose.slides.PointF** | End point |
| index | **int** | Index of segment in PathData |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segment index is out of PathData range |


## quadratic_bezier_to(self, x1, y1, x2, y2) {#float-float-float-float}
Ajoute une courbe de Bézier quadratique à la fin du chemin


```python
def quadratic_bezier_to(self, x1, y1, x2, y2):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| x1 | **float** | X coordinate of direction point |
| y1 | **float** | Y coordinate of direction point |
| x2 | **float** | X coordinate of end point |
| y2 | **float** | Y coordinate of end point |


## quadratic_bezier_to(self, x1, y1, x2, y2, index) {#float-float-float-float-int}
Ajoute une courbe de Bézier quadratique à l'emplacement spécifié du chemin


```python
def quadratic_bezier_to(self, x1, y1, x2, y2, index):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| x1 | **float** | X coordinate of direction point |
| y1 | **float** | Y coordinate of direction point |
| x2 | **float** | X coordinate of end point |
| y2 | **float** | Y coordinate of end point |
| index | **int** | Index of segment in PathData |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segment index is out of PathData range |



### Voir aussi
* classe [`IGeometryPath`](/slides/python-net/fr/aspose.slides/igeometrypath)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)