---
title: line_to method
second_title: Tham chiếu API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides/geometrypath/line_to/
weight: 50
---
## line_to(self, point) {#asposepydrawingpointf}
Thêm đường thẳng vào cuối đường dẫn


```python
def line_to(self, point):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| point | **aspose.slides.PointF** | Điểm cuối của đường thẳng |


## line_to(self, x, y) {#float-float}
Thêm đường thẳng vào cuối đường dẫn


```python
def line_to(self, x, y):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| x | **float** | Tọa độ X của điểm cuối của đường thẳng |
| y | **float** | Tọa độ Y của điểm cuối của đường thẳng |


## line_to(self, point, index) {#asposepydrawingpointf-int}
Thêm đường thẳng vào vị trí chỉ định của đường dẫn


```python
def line_to(self, point, index):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| point | **aspose.slides.PointF** | Điểm cuối |
| index | **int** | Chỉ mục của đoạn trong PathData |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Chỉ mục đoạn vượt quá phạm vi PathData |


## line_to(self, x, y, index) {#float-float-int}
Thêm đường thẳng vào vị trí chỉ định của đường dẫn


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
* lớp [`GeometryPath`](/slides/python-net/vi/aspose.slides/geometrypath)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)