---
title: contains method
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/rectanglef/contains/
weight: 20
---
## contains(self, point) {#pointf}
Bestimmt, ob der angegebene Punkt innerhalb dieses Rechtecks liegt.

### Rückgabewert

`True` wenn der Punkt innerhalb dieses Rechtecks liegt; sonst `False`.



```python
def contains(self, point):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/de/aspose.slides/pointf) | Der zu testende Punkt. Jedes Objekt mit den Attributen `x` und `y` wird akzeptiert. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **TypeError** | Falsche Anzahl von Argumenten. |


## contains(self, rect) {#rectanglef}
Bestimmt, ob der durch `rect` dargestellte rechteckige Bereich vollständig innerhalb dieses Rechtecks liegt.

### Rückgabewert

`True` wenn der durch `rect` dargestellte rechteckige Bereich vollständig innerhalb dieses Rechtecks liegt; sonst `False`.



```python
def contains(self, rect):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [`RectangleF`](/slides/python-net/de/aspose.slides/rectanglef) | Das zu testende Rechteck. Jedes Objekt mit den Attributen `x`, `y`, `width` und `height` wird akzeptiert. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **TypeError** | Falsche Anzahl von Argumenten. |


## contains(self, x, y) {#float-float}
Bestimmt, ob der angegebene Punkt innerhalb dieses Rechtecks liegt.

### Rückgabewert

`True` wenn der durch `x` und `y` definierte Punkt innerhalb dieses Rechtecks liegt; sonst `False`.



```python
def contains(self, x, y):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | **float** | Die x-Koordinate des zu testenden Punktes. |
| y | **float** | Die y-Koordinate des zu testenden Punktes. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **TypeError** | Falsche Anzahl von Argumenten. |



### Siehe auch
* class [`PointF`](/slides/python-net/de/aspose.slides/pointf)
* class [`RectangleF`](/slides/python-net/de/aspose.slides/rectanglef)
* module [`aspose.slides`](/slides/python-net/de/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)