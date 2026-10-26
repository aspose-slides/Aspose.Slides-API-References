---
title: line_to method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/igeometrypath/line_to/
weight: 40
---
## line_to(self, point) {#asposeslidespointf}
Thêm đoạn vào cuối đường dẫn


```python
def line_to(self, point):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/vi/aspose.slides/pointf) | Điểm cuối của đoạn |


## line_to(self, x, y) {#float-float}
Thêm đoạn vào cuối đường dẫn


```python
def line_to(self, x, y):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| x | **float** | Tọa độ X của điểm cuối của đoạn |
| y | **float** | Tọa độ Y của điểm cuối của đoạn |


## line_to(self, point, index) {#asposeslidespointf-int}
Thêm đoạn vào vị trí chỉ định của đường dẫn


```python
def line_to(self, point, index):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/vi/aspose.slides/pointf) | Điểm cuối |
| index | **int** | Chỉ mục của đoạn trong PathData |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Chỉ mục đoạn vượt quá phạm vi PathData |


## line_to(self, x, y, index) {#float-float-int}
Thêm đoạn vào vị trí chỉ định của đường dẫn


```python
def line_to(self, x, y, index):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| x | **float** | Tọa độ X của điểm |
| y | **float** | Tọa độ Y của điểm |
| index | **int** | Chỉ mục của đoạn trong PathData |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Chỉ mục đoạn vượt quá phạm vi PathData |



### Xem thêm
* lớp [`IGeometryPath`](/slides/python-net/vi/aspose.slides/igeometrypath)
* lớp [`PointF`](/slides/python-net/vi/aspose.slides/pointf)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)