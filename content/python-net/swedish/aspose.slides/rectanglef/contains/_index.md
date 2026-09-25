---
title: contains method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/rectanglef/contains/
weight: 20
---
## contains(self, point) {#pointf}
Avgör om den angivna punkten ligger inom denna rektangel.

### Returnerar

`True` om punkten ligger inom denna rektangel; annars `False`.



```python
def contains(self, point):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/sv/aspose.slides/pointf) | Punkten att testa. Alla objekt med `x` och `y` attribut accepteras. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **TypeError** | Fel antal argument. |


## contains(self, rect) {#rectanglef}
Avgör om det rektangulära området som representeras av `rect` helt ligger inom denna rektangel.

### Returnerar

`True` om det rektangulära området som representeras av `rect` helt ligger inom denna rektangel; annars `False`.



```python
def contains(self, rect):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [`RectangleF`](/slides/python-net/sv/aspose.slides/rectanglef) | Rektangeln att testa. Alla objekt med `x`, `y`, `width` och `height` attribut accepteras. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **TypeError** | Fel antal argument. |


## contains(self, x, y) {#float-float}
Avgör om den angivna punkten ligger inom denna rektangel.

### Returnerar

`True` om punkten definierad av `x` och `y` ligger inom denna rektangel; annars `False`.



```python
def contains(self, x, y):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | **float** | X-koordinaten för punkten att testa. |
| y | **float** | Y-koordinaten för punkten att testa. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **TypeError** | Fel antal argument. |



### Se också
* klass [`PointF`](/slides/python-net/sv/aspose.slides/pointf)
* klass [`RectangleF`](/slides/python-net/sv/aspose.slides/rectanglef)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)