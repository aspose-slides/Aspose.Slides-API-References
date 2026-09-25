---
title: contains method
second_title: Aspose.Slides pro Python přes .NET – referenční příručka
description: 
type: docs
url: /cs/aspose.slides/rectangle/contains/
weight: 20
---
## contains(self, point) {#point}
Určuje, zda je zadaný bod obsažen v tomto obdélníku.

### Returns

`True` pokud je bod obsažen v tomto obdélníku; jinak `False`.



```python
def contains(self, point):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| point | [`Point`](/slides/python-net/cs/aspose.slides/point) | Bod k testování. Je přijímán jakýkoli objekt s atributy `x` a `y`. |

### Exceptions

| Výjimka | Popis |
| :- | :- |
| **TypeError** | Nesprávný počet argumentů. |


## contains(self, rect) {#rectangle}
Určuje, zda je oblast obdélníku reprezentovaná `rect` zcela obsažena v tomto obdélníku.

### Returns

`True` pokud je oblast obdélníku reprezentovaná `rect` zcela obsažena v tomto obdélníku; jinak `False`.



```python
def contains(self, rect):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| rect | [`Rectangle`](/slides/python-net/cs/aspose.slides/rectangle) | Obdélník k testování. Je přijímán jakýkoli objekt s atributy `x`, `y`, `width` a `height`. |

### Exceptions

| Výjimka | Popis |
| :- | :- |
| **TypeError** | Nesprávný počet argumentů. |


## contains(self, x, y) {#int-int}
Určuje, zda je zadaný bod obsažen v tomto obdélníku.

### Returns

`True` pokud je bod definovaný `x` a `y` obsažen v tomto obdélníku; jinak `False`.



```python
def contains(self, x, y):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| x | **int** | X-souřadnice bodu k testování. |
| y | **int** | Y-souřadnice bodu k testování. |

### Exceptions

| Výjimka | Popis |
| :- | :- |
| **TypeError** | Nesprávný počet argumentů. |



### See Also
* třída [`Point`](/slides/python-net/cs/aspose.slides/point)
* třída [`Rectangle`](/slides/python-net/cs/aspose.slides/rectangle)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)