---
title: contains method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/rectanglef/contains/
weight: 20
---
## contains(self, point) {#pointf}
Bepaalt of het opgegeven punt zich binnen deze rechthoek bevindt.

### Retourwaarde

`True` als het punt zich binnen deze rechthoek bevindt; anders `False`.



```python
def contains(self, point):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/nl/aspose.slides/pointf) | Het punt om te testen. Elk object met `x` en `y` attributen wordt geaccepteerd. |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **TypeError** | Verkeerd aantal argumenten. |


## contains(self, rect) {#rectanglef}
Bepaalt of het door `rect` vertegenwoordigde rechthoekige gebied volledig binnen deze rechthoek valt.

### Retourwaarde

`True` als het door `rect` vertegenwoordigde rechthoekige gebied volledig binnen deze rechthoek valt; anders `False`.



```python
def contains(self, rect):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rect | [`RectangleF`](/slides/python-net/nl/aspose.slides/rectanglef) | De rechthoek om te testen. Elk object met `x`, `y`, `width` en `height` attributen wordt geaccepteerd. |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **TypeError** | Verkeerd aantal argumenten. |


## contains(self, x, y) {#float-float}
Bepaalt of het opgegeven punt zich binnen deze rechthoek bevindt.

### Retourwaarde

`True` als het door `x` en `y` gedefinieerde punt zich binnen deze rechthoek bevindt; anders `False`.



```python
def contains(self, x, y):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x | **float** | De x-coördinaat van het te testen punt. |
| y | **float** | De y-coördinaat van het te testen punt. |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **TypeError** | Verkeerd aantal argumenten. |



### Zie ook
* klasse [`PointF`](/slides/python-net/nl/aspose.slides/pointf)
* klasse [`RectangleF`](/slides/python-net/nl/aspose.slides/rectanglef)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)