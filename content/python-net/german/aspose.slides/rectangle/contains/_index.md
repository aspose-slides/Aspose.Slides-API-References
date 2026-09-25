---
title: contains method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/rectangle/contains/
weight: 20
---
## contains(self, point) {#point}
Bestimmt, ob der angegebene Punkt innerhalb dieses Rechtecks liegt.

### Rückgabewert

`True` wenn der Punkt innerhalb dieses Rechtecks liegt; andernfalls `False`.



```python
def contains(self, point):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [`Point`](/slides/python-net/de/aspose.slides/point) | Der zu testende Punkt. Jedes Objekt mit den Attributen `x` und `y` wird akzeptiert. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **TypeError** | Falsche Anzahl von Argumenten. |


## contains(self, rect) {#rectangle}
Bestimmt, ob der durch `rect` dargestellte rechteckige Bereich vollständig innerhalb dieses Rechtecks liegt.

### Rückgabewert

`True` wenn der durch `rect` dargestellte rechteckige Bereich vollständig innerhalb dieses Rechtecks liegt; andernfalls `False`.



```python
def contains(self, rect):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [`Rectangle`](/slides/python-net/de/aspose.slides/rectangle) | Das zu testende Rechteck. Jedes Objekt mit den Attributen `x`, `y`, `width` und `height` wird akzeptiert. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **TypeError** | Falsche Anzahl von Argumenten. |


## contains(self, x, y) {#int-int}
Bestimmt, ob der angegebene Punkt innerhalb dieses Rechtecks liegt.

### Rückgabewert

`True` wenn der durch `x` und `y` definierte Punkt innerhalb dieses Rechtecks liegt; andernfalls `False`.



```python
def contains(self, x, y):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | **int** | Die x-Koordinate des zu testenden Punktes. |
| y | **int** | Die y-Koordinate des zu testenden Punktes. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **TypeError** | Falsche Anzahl von Argumenten. |



### Siehe auch
* Klasse [`Point`](/slides/python-net/de/aspose.slides/point)
* Klasse [`Rectangle`](/slides/python-net/de/aspose.slides/rectangle)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)