---
title: line_to method
second_title: Aspose.Slides برای Python از طریق API مرجع .NET
description: 
type: docs
url: /fa/aspose.slides/geometrypath/line_to/
weight: 50
---
## line_to(self, point) {#asposeslidespointf}
خطی به انتهای مسیر اضافه می‌کند


```python
def line_to(self, point):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/fa/aspose.slides/pointf) | نقطه انتهایی خط |


## line_to(self, x, y) {#float-float}
خطی به انتهای مسیر اضافه می‌کند


```python
def line_to(self, x, y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | مختصات X نقطه انتهایی خط |
| y | **float** | مختصات Y نقطه انتهایی خط |


## line_to(self, point, index) {#asposeslidespointf-int}
خطی به محل مشخصی از مسیر اضافه می‌کند


```python
def line_to(self, point, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/fa/aspose.slides/pointf) | نقطه انتهایی |
| index | **int** | اندیس بخش در PathData |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | اندیس بخش خارج از محدوده PathData است |


## line_to(self, x, y, index) {#float-float-int}
خطی به محل مشخصی از مسیر اضافه می‌کند


```python
def line_to(self, x, y, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | مختصات X نقطه |
| y | **float** | مختصات Y نقطه |
| index | **int** | اندیس بخش در PathData |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | اندیس بخش خارج از محدوده PathData است |



### See Also
* class [`GeometryPath`](/slides/python-net/fa/aspose.slides/geometrypath)
* class [`PointF`](/slides/python-net/fa/aspose.slides/pointf)
* module [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)