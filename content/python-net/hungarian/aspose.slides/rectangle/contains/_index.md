---
title: contains method
second_title: Aspose.Slides for Python via .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides/rectangle/contains/
weight: 20
---
## contains(self, point) {#point}
Megállapítja, hogy a megadott pont benne van-e ebben a téglalapban.

### Visszatérési érték

`True` ha a pont benne van ebben a téglalapban; egyébként `False`.



```python
def contains(self, point):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| point | [`Point`](/slides/python-net/hu/aspose.slides/point) | A tesztelendő pont. Bármely objektum, amely `x` és `y` attribútummal rendelkezik, elfogadott. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **TypeError** | Wrong number of arguments. |


## contains(self, rect) {#rectangle}
Megállapítja, hogy a `rect` által képviselt téglalap-régió teljesen benne van-e ebben a téglalapban.

### Visszatérési érték

`True` ha a `rect` által képviselt téglalap-régió teljesen benne van ebben a téglalapban; egyébként `False`.



```python
def contains(self, rect):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| rect | [`Rectangle`](/slides/python-net/hu/aspose.slides/rectangle) | A tesztelendő téglalap. Bármely objektum, amely `x`, `y`, `width` és `height` attribútumokkal rendelkezik, elfogadott. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **TypeError** | Wrong number of arguments. |


## contains(self, x, y) {#int-int}
Megállapítja, hogy a megadott pont benne van-e ebben a téglalapban.

### Visszatérési érték

`True` ha a `x` és `y` által meghatározott pont benne van ebben a téglalapban; egyébként `False`.



```python
def contains(self, x, y):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| x | **int** | A tesztelendő pont x-koordinátája. |
| y | **int** | A tesztelendő pont y-koordinátája. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **TypeError** | Wrong number of arguments. |



### Lásd még
* osztály [`Point`](/slides/python-net/hu/aspose.slides/point)
* osztály [`Rectangle`](/slides/python-net/hu/aspose.slides/rectangle)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)