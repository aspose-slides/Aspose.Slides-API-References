---
title: contains method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/rectangle/contains/
weight: 20
---
## contains(self, point) {#point}
Belirtilen noktanın bu dikdörtgen içinde olup olmadığını belirler.

### Döndürür

`True` if the point is contained within this rectangle; otherwise, `False`.



```python
def contains(self, point):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| point | [`Point`](/slides/python-net/tr/aspose.slides/point) | Test edilecek nokta. `x` ve `y` niteliklerine sahip herhangi bir nesne kabul edilir. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **TypeError** | Yanlış sayıda argüman. |


## contains(self, rect) {#rectangle}
`rect` tarafından temsil edilen dikdörtgen bölgenin tamamen bu dikdörtgen içinde olup olmadığını belirler.

### Döndürür

`True` if the rectangular region represented by `rect` is entirely contained within this rectangle; otherwise, `False`.



```python
def contains(self, rect):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rect | [`Rectangle`](/slides/python-net/tr/aspose.slides/rectangle) | Test edilecek dikdörtgen. `x`, `y`, `width` ve `height` niteliklerine sahip herhangi bir nesne kabul edilir. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **TypeError** | Yanlış sayıda argüman. |


## contains(self, x, y) {#int-int}
Belirtilen noktanın bu dikdörtgen içinde olup olmadığını belirler.

### Döndürür

`True` if the point defined by `x` and `y` is contained within this rectangle; otherwise, `False`.



```python
def contains(self, x, y):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | **int** | Test edilecek noktanın x koordinatı. |
| y | **int** | Test edilecek noktanın y koordinatı. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **TypeError** | Yanlış sayıda argüman. |



### Ayrıca Bakınız
* sınıf [`Point`](/slides/python-net/tr/aspose.slides/point)
* sınıf [`Rectangle`](/slides/python-net/tr/aspose.slides/rectangle)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)