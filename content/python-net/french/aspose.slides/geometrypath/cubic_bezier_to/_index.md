---
title: cubic_bezier_to method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/geometrypath/cubic_bezier_to/
weight: 40
---
## cubic_bezier_to(self, point1, point2, point3) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf}
Ajoute une courbe de Bézier cubique à la fin du chemin


```python
def cubic_bezier_to(self, point1, point2, point3):
    ...
```



| Paramètre | Type | Description |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Premier point de direction |
| point2 | **aspose.slides.PointF** | Deuxième point de direction |
| point3 | **aspose.slides.PointF** | Point final |


## cubic_bezier_to(self, point1, point2, point3, index) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int}
Ajoute une courbe de Bézier cubique à l'emplacement spécifié du chemin


```python
def cubic_bezier_to(self, point1, point2, point3, index):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Premier point de direction |
| point2 | **aspose.slides.PointF** | Deuxième point de direction |
| point3 | **aspose.slides.PointF** | Point final |
| index | **int** | Index du segment dans PathData |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | L'index du segment est hors de la plage de PathData |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3) {#float-float-float-float-float-float}
Ajoute une courbe de Bézier cubique à la fin du chemin


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| x1 | **float** | Coordonnée X du premier point de direction |
| y1 | **float** | Coordonnée Y du premier point de direction |
| x2 | **float** | Coordonnée X du deuxième point de direction |
| y2 | **float** | Coordonnée Y du deuxième point de direction |
| x3 | **float** | Coordonnée X du point final |
| y3 | **float** | Coordonnée Y du point final |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index) {#float-float-float-float-float-float-int}
Ajoute une courbe de Bézier cubique à l'emplacement spécifié du chemin


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| x1 | **float** | Coordonnée X du premier point de direction |
| y1 | **float** | Coordonnée Y du premier point de direction |
| x2 | **float** | Coordonnée X du deuxième point de direction |
| y2 | **float** | Coordonnée Y du deuxième point de direction |
| x3 | **float** | Coordonnée X du point final |
| y3 | **float** | Coordonnée Y du point final |
| index | **int** | Index du segment dans PathData |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | L'index du segment est hors de la plage de PathData |



### See Also
* classe [`GeometryPath`](/slides/python-net/fr/aspose.slides/geometrypath)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)