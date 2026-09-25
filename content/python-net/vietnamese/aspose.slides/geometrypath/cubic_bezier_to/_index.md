---
title: cubic_bezier_to method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/geometrypath/cubic_bezier_to/
weight: 40
---
## cubic_bezier_to(self, point1, point2, point3) {#asposeslidespointf-asposeslidespointf-asposeslidespointf}
Thêm đường cong Bezier bậc ba vào cuối đường dẫn


```python
def cubic_bezier_to(self, point1, point2, point3):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/vi/aspose.slides/pointf) | Điểm hướng đầu tiên |
| point2 | [`PointF`](/slides/python-net/vi/aspose.slides/pointf) | Điểm hướng thứ hai |
| point3 | [`PointF`](/slides/python-net/vi/aspose.slides/pointf) | Điểm cuối |


## cubic_bezier_to(self, point1, point2, point3, index) {#asposeslidespointf-asposeslidespointf-asposeslidespointf-int}
Thêm đường cong Bezier bậc ba vào vị trí đã chỉ định của đường dẫn


```python
def cubic_bezier_to(self, point1, point2, point3, index):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/vi/aspose.slides/pointf) | Điểm hướng đầu tiên |
| point2 | [`PointF`](/slides/python-net/vi/aspose.slides/pointf) | Điểm hướng thứ hai |
| point3 | [`PointF`](/slides/python-net/vi/aspose.slides/pointf) | Điểm cuối |
| index | **int** | Chỉ mục của đoạn trong PathData |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Chỉ mục đoạn vượt ra ngoài phạm vi của PathData |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3) {#float-float-float-float-float-float}
Thêm đường cong Bezier bậc ba vào cuối đường dẫn


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| x1 | **float** | Tọa độ X của điểm hướng đầu tiên |
| y1 | **float** | Tọa độ Y của điểm hướng đầu tiên |
| x2 | **float** | Tọa độ X của điểm hướng thứ hai |
| y2 | **float** | Tọa độ Y của điểm hướng thứ hai |
| x3 | **float** | Tọa độ X của điểm cuối |
| y3 | **float** | Tọa độ Y của điểm cuối |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index) {#float-float-float-float-float-float-int}
Thêm đường cong Bezier bậc ba vào vị trí đã chỉ định của đường dẫn


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| x1 | **float** | Tọa độ X của điểm hướng đầu tiên |
| y1 | **float** | Tọa độ Y của điểm hướng đầu tiên |
| x2 | **float** | Tọa độ X của điểm hướng thứ hai |
| y2 | **float** | Tọa độ Y của điểm hướng thứ hai |
| x3 | **float** | Tọa độ X của điểm cuối |
| y3 | **float** | Tọa độ Y của điểm cuối |
| index | **int** | Chỉ mục của đoạn trong PathData |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Chỉ mục đoạn vượt ra ngoài phạm vi của PathData |



### Xem thêm
* lớp [`GeometryPath`](/slides/python-net/vi/aspose.slides/geometrypath)
* lớp [`PointF`](/slides/python-net/vi/aspose.slides/pointf)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)