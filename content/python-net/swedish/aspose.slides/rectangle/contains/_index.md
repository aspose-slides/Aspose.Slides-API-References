---
title: contains method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/rectangle/contains/
weight: 20
---
## contains(self, point) {#point}
Bestämmer om den angivna punkten ligger inom den här rektangeln.

### Returnerar

`True` om punkten ligger inom den här rektangeln; annars `False`.



```python
def contains(self, point):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [`Point`](/slides/python-net/sv/aspose.slides/point) | Punkten som ska testas. Alla objekt med attributen `x` och `y` accepteras. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **TypeError** | Fel antal argument. |


## contains(self, rect) {#rectangle}
Bestämmer om det rektangulära området som representeras av `rect` är helt inneslutet i den här rektangeln.

### Returnerar

`True` om det rektangulära området som representeras av `rect` är helt inneslutet i den här rektangeln; annars `False`.



```python
def contains(self, rect):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [`Rectangle`](/slides/python-net/sv/aspose.slides/rectangle) | Rektangeln som ska testas. Alla objekt med attributen `x`, `y`, `width` och `height` accepteras. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **TypeError** | Fel antal argument. |


## contains(self, x, y) {#int-int}
Bestämmer om den angivna punkten ligger inom den här rektangeln.

### Returnerar

`True` om punkten som definieras av `x` och `y` ligger inom den här rektangeln; annars `False`.



```python
def contains(self, x, y):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | **int** | x-koordinaten för den punkt som ska testas. |
| y | **int** | y-koordinaten för den punkt som ska testas. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **TypeError** | Fel antal argument. |



### Se även
* klass [`Point`](/slides/python-net/sv/aspose.slides/point)
* klass [`Rectangle`](/slides/python-net/sv/aspose.slides/rectangle)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)