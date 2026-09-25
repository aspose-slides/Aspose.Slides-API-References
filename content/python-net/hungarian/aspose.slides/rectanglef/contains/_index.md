---
title: contains method
second_title: Aspose.Slides for Python via .NET API referencia
description: 
type: docs
url: /hu/aspose.slides/rectanglef/contains/
weight: 20
---
## contains(self, point) {#pointf}
Megállapítja, hogy a megadott pont benne van-e ebben a téglalapban.

### Visszatérési érték

`True` ha a pont benne van ebben a téglalapban; egyébként `False`.



```python
def contains(self, point):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/hu/aspose.slides/pointf) | A tesztelendő pont. Bármely olyan objektum, amely rendelkezik `x` és `y` attribútumokkal, elfogadott. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **TypeError** | Hibás számú argumentum. |


## contains(self, rect) {#rectanglef}
Megállapítja, hogy a `rect` által reprezentált téglalap teljes egészében benne van-e ebben a téglalapban.

### Visszatérési érték

`True` ha a `rect` által reprezentált téglalap teljes egészében benne van ebben a téglalapban; egyébként `False`.



```python
def contains(self, rect):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| rect | [`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef) | A tesztelendő téglalap. Bármely olyan objektum, amely rendelkezik `x`, `y`, `width` és `height` attribútumokkal, elfogadott. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **TypeError** | Hibás számú argumentum. |


## contains(self, x, y) {#float-float}
Megállapítja, hogy a megadott pont benne van-e ebben a téglalapban.

### Visszatérési érték

`True` ha az `x` és `y` által definiált pont benne van ebben a téglalapban; egyébként `False`.



```python
def contains(self, x, y):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| x | **float** | A tesztelendő pont x koordinátája. |
| y | **float** | A tesztelendő pont y koordinátája. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **TypeError** | Hibás számú argumentum. |



### Lásd még
* osztály [`PointF`](/slides/python-net/hu/aspose.slides/pointf)
* osztály [`RectangleF`](/slides/python-net/hu/aspose.slides/rectanglef)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)