---
title: quadratic_bezier_to method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/igeometrypath/quadratic_bezier_to/
weight: 60
---
## quadratic_bezier_to(self, point1, point2) {#asposeslidespointf-asposeslidespointf}
Ajoute une courbe de Bézier quadratique à la fin du chemin


```python
def quadratic_bezier_to(self, point1, point2):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/fr/aspose.slides/pointf) | Point de direction |
| point2 | [`PointF`](/slides/python-net/fr/aspose.slides/pointf) | Point final |


## quadratic_bezier_to(self, point1, point2, index) {#asposeslidespointf-asposeslidespointf-int}
Ajoute une courbe de Bézier quadratique à l'emplacement spécifié du chemin


```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/fr/aspose.slides/pointf) | Point de direction |
| point2 | [`PointF`](/slides/python-net/fr/aspose.slides/pointf) | Point final |
| index | **int** | Indice du segment dans PathData |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | L'indice du segment est hors de la plage de PathData |


## quadratic_bezier_to(self, x1, y1, x2, y2) {#float-float-float-float}
Ajoute une courbe de Bézier quadratique à la fin du chemin


```python
def quadratic_bezier_to(self, x1, y1, x2, y2):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| x1 | **float** | Coordonnée X du point de direction |
| y1 | **float** | Coordonnée Y du point de direction |
| x2 | **float** | Coordonnée X du point final |
| y2 | **float** | Coordonnée Y du point final |


## quadratic_bezier_to(self, x1, y1, x2, y2, index) {#float-float-float-float-int}
Ajoute une courbe de Bézier quadratique à l'emplacement spécifié du chemin


```python
def quadratic_bezier_to(self, x1, y1, x2, y2, index):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| x1 | **float** | Coordonnée X du point de direction |
| y1 | **float** | Coordonnée Y du point de direction |
| x2 | **float** | Coordonnée X du point final |
| y2 | **float** | Coordonnée Y du point final |
| index | **int** | Indice du segment dans PathData |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | L'indice du segment est hors de la plage de PathData |



### Voir aussi
* classe [`IGeometryPath`](/slides/python-net/fr/aspose.slides/igeometrypath)
* classe [`PointF`](/slides/python-net/fr/aspose.slides/pointf)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)