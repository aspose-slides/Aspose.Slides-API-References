---
title: line_to method
second_title: Tham chiếu API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides/geometrypath/line_to/
weight: 50
---
## line_to(self, point) {#asposeslidespointf}
Thêm đoạn thẳng vào cuối đường dẫn


```python
def line_to(self, point):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/vi/aspose.slides/pointf) | Điểm cuối của đoạn thẳng |


## line_to(self, x, y) {#float-float}
Thêm đoạn thẳng vào cuối đường dẫn


```python
def line_to(self, x, y):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| x | **float** | Tọa độ X của điểm cuối của đoạn thẳng |
| y | **float** | Tọa độ Y của điểm cuối của đoạn thẳng |


## line_to(self, point, index) {#asposeslidespointf-int}
Thêm đoạn thẳng vào vị trí được chỉ định trong đường dẫn


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
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Chỉ mục đoạn nằm ngoài phạm vi PathData |


## line_to(self, x, y, index) {#float-float-int}
Thêm đoạn thẳng vào vị trí được chỉ định trong đường dẫn


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
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Chỉ mục đoạn nằm ngoài phạm vi PathData |



### Xem thêm
* lớp [`GeometryPath`](/slides/python-net/vi/aspose.slides/geometrypath)
* lớp [`PointF`](/slides/python-net/vi/aspose.slides/pointf)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)