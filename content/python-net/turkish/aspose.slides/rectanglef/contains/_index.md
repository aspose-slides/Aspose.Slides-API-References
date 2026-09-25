---
title: contains method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/rectanglef/contains/
weight: 20
---
## contains(self, point) {#pointf}
Belirtilen noktanın bu dikdörtgen içinde olup olmadığını belirler.

### Dönüş Değeri

`True` if the point is contained within this rectangle; otherwise, `False`.



```python
def contains(self, point):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/tr/aspose.slides/pointf) | Test edilecek nokta. `x` ve `y` özniteliklerine sahip herhangi bir nesne kabul edilir. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **TypeError** | Yanlış sayıda argüman. |


## contains(self, rect) {#rectanglef}
`rect` tarafından temsil edilen dikdörtgen bölgenin bu dikdörtgen içinde tamamen olup olmadığını belirler.

### Dönüş Değeri

`True` if the rectangular region represented by `rect` is entirely contained within this rectangle; otherwise, `False`.



```python
def contains(self, rect):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rect | [`RectangleF`](/slides/python-net/tr/aspose.slides/rectanglef) | Test edilecek dikdörtgen. `x`, `y`, `width` ve `height` özniteliklerine sahip herhangi bir nesne kabul edilir. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **TypeError** | Yanlış sayıda argüman. |


## contains(self, x, y) {#float-float}
Belirtilen noktanın bu dikdörtgen içinde olup olmadığını belirler.

### Dönüş Değeri

`True` if the point defined by `x` and `y` is contained within this rectangle; otherwise, `False`.



```python
def contains(self, x, y):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | **float** | Test edilecek noktanın x koordinatı. |
| y | **float** | Test edilecek noktanın y koordinatı. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **TypeError** | Yanlış sayıda argüman. |



### Ayrıca Bakınız
* sınıf [`PointF`](/slides/python-net/tr/aspose.slides/pointf)
* sınıf [`RectangleF`](/slides/python-net/tr/aspose.slides/rectanglef)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)