---
title: contains method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/rectanglef/contains/
weight: 20
---
## contains(self, point) {#pointf}
Určuje, zda je zadaný bod obsažen v tomto obdélníku.

### Návratová hodnota

`True` pokud je bod obsažen v tomto obdélníku; jinak `False`.



```python
def contains(self, point):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/cs/aspose.slides/pointf) | Bod k testování. Je přijat jakýkoli objekt s atributy `x` a `y`. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **TypeError** | Špatný počet argumentů. |


## contains(self, rect) {#rectanglef}
Určuje, zda je oblast obdélníku reprezentovaná `rect` zcela obsažena v tomto obdélníku.

### Návratová hodnota

`True` pokud je oblast obdélníku reprezentovaná `rect` zcela obsažena v tomto obdélníku; jinak `False`.



```python
def contains(self, rect):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| rect | [`RectangleF`](/slides/python-net/cs/aspose.slides/rectanglef) | Obdélník k testování. Je přijat jakýkoli objekt s atributy `x`, `y`, `width` a `height`. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **TypeError** | Špatný počet argumentů. |


## contains(self, x, y) {#float-float}
Určuje, zda je zadaný bod obsažen v tomto obdélníku.

### Návratová hodnota

`True` pokud je bod definovaný `x` a `y` obsažen v tomto obdélníku; jinak `False`.



```python
def contains(self, x, y):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| x | **float** | X-souřadnice bodu k testování. |
| y | **float** | Y-souřadnice bodu k testování. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **TypeError** | Špatný počet argumentů. |



### Viz také
* třída [`PointF`](/slides/python-net/cs/aspose.slides/pointf)
* třída [`RectangleF`](/slides/python-net/cs/aspose.slides/rectanglef)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)