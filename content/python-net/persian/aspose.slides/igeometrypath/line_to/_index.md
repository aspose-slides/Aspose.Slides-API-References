---
title: line_to method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/igeometrypath/line_to/
weight: 40
---
## line_to(self, point) {#asposepydrawingpointf}
خطی را به انتهای مسیر اضافه می‌کند


```python
def line_to(self, point):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| point | **aspose.slides.PointF** | نقطه انتهایی خط |


## line_to(self, x, y) {#float-float}
خطی را به انتهای مسیر اضافه می‌کند


```python
def line_to(self, x, y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | مختصات X نقطه انتهایی خط |
| y | **float** | مختصات Y نقطه انتهایی خط |


## line_to(self, point, index) {#asposepydrawingpointf-int}
خطی را به مکان مشخصی از مسیر اضافه می‌کند


```python
def line_to(self, point, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| point | **aspose.slides.PointF** | نقطه انتهایی |
| index | **int** | اندیس بخش در PathData |

### استثناها

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | اندیس بخش خارج از محدوده PathData است |


## line_to(self, x, y, index) {#float-float-int}
خطی را به مکان مشخصی از مسیر اضافه می‌کند


```python
def line_to(self, x, y, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | مختصات X نقطه |
| y | **float** | مختصات Y نقطه |
| index | **int** | اندیس بخش در PathData |

### استثناها

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | اندیس بخش خارج از محدوده PathData است |



### موارد مرتبط
* کلاس [`IGeometryPath`](/slides/python-net/fa/aspose.slides/igeometrypath)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)