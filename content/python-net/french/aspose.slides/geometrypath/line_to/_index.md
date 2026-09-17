---
title: line_to method
second_title: Aspose.Slides pour Python via .NET Référence API
description: 
type: docs
url: /fr/aspose.slides/geometrypath/line_to/
weight: 50
---
## line_to(self, point) {#asposepydrawingpointf}
Ajoute une ligne à la fin du chemin


```python
def line_to(self, point):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| point | **aspose.slides.PointF** | Point final de la ligne |


## line_to(self, x, y) {#float-float}
Ajoute une ligne à la fin du chemin


```python
def line_to(self, x, y):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| x | **float** | Coordonnée X du point final de la ligne |
| y | **float** | Coordonnée Y du point final de la ligne |


## line_to(self, point, index) {#asposepydrawingpointf-int}
Ajoute une ligne à l'emplacement spécifié du chemin


```python
def line_to(self, point, index):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| point | **aspose.slides.PointF** | Point final |
| index | **int** | Index du segment dans PathData |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | L'index du segment est hors de la plage de PathData |


## line_to(self, x, y, index) {#float-float-int}
Ajoute une ligne à l'emplacement spécifié du chemin


```python
def line_to(self, x, y, index):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| x | **float** | Coordonnée X du point |
| y | **float** | Coordonnée Y du point |
| index | **int** | Index du segment dans PathData |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | L'index du segment est hors de la plage de PathData |



### Voir aussi
* classe [`GeometryPath`](/slides/python-net/fr/aspose.slides/geometrypath)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)