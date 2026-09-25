---
title: contains method
second_title: مرجع API لـ Aspose.Slides للـ Python عبر .NET
description: 
type: docs
url: /ar/aspose.slides/rectanglef/contains/
weight: 20
---
## contains(self, point) {#pointf}
تحدد ما إذا كانت النقطة المحددة داخل هذا المستطيل.

### Returns
`True` إذا كانت النقطة داخل هذا المستطيل؛ وإلا `False`.



```python
def contains(self, point):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/ar/aspose.slides/pointf) | النقطة التي سيتم اختبارها. يُقبل أي كائن يحتوي على خاصيتي `x` و `y`. |

### Exceptions
| Exception | Description |
| :- | :- |
| **TypeError** | عدد غير صحيح من المعاملات. |


## contains(self, rect) {#rectanglef}
تحدد ما إذا كانت المنطقة المستطيلة التي يمثلها `rect` متضمنة بالكامل داخل هذا المستطيل.

### Returns
`True` إذا كانت المنطقة المستطيلة التي يمثلها `rect` متضمنة بالكامل داخل هذا المستطيل؛ وإلا `False`.



```python
def contains(self, rect):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| rect | [`RectangleF`](/slides/python-net/ar/aspose.slides/rectanglef) | المستطيل الذي سيتم اختباره. يُقبل أي كائن يحتوي على خاصيات `x` و `y` و `width` و `height`. |

### Exceptions
| Exception | Description |
| :- | :- |
| **TypeError** | عدد غير صحيح من المعاملات. |


## contains(self, x, y) {#float-float}
تحدد ما إذا كانت النقطة المحددة داخل هذا المستطيل.

### Returns
`True` إذا كانت النقطة المحددة بـ `x` و `y` داخل هذا المستطيل؛ وإلا `False`.



```python
def contains(self, x, y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | الإحداثي السيني للنقطة التي سيتم اختبارها. |
| y | **float** | الإحداثي الصادي للنقطة التي سيتم اختبارها. |

### Exceptions
| Exception | Description |
| :- | :- |
| **TypeError** | عدد غير صحيح من المعاملات. |



### See Also
* فئة [`PointF`](/slides/python-net/ar/aspose.slides/pointf)
* فئة [`RectangleF`](/slides/python-net/ar/aspose.slides/rectanglef)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)