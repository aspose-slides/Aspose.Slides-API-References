---
title: quadratic_bezier_to method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/geometrypath/quadratic_bezier_to/
weight: 70
---
## quadratic_bezier_to(self, point1, point2) {#asposeslidespointf-asposeslidespointf}
Thêm đường cong Bezier bậc hai vào cuối đường


```python
def quadratic_bezier_to(self, point1, point2):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/vi/aspose.slides/pointf) | Điểm điều hướng |
| point2 | [`PointF`](/slides/python-net/vi/aspose.slides/pointf) | Điểm cuối |


## quadratic_bezier_to(self, point1, point2, index) {#asposeslidespointf-asposeslidespointf-int}
Thêm đường cong Bezier bậc hai vào vị trí được chỉ định của đường


```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/vi/aspose.slides/pointf) | Điểm điều hướng |
| point2 | [`PointF`](/slides/python-net/vi/aspose.slides/pointf) | Điểm cuối |
| index | **int** | Chỉ số của đoạn trong PathData |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Chỉ số đoạn vượt ra ngoài phạm vi PathData |


## quadratic_bezier_to(self, x1, y1, x2, y2) {#float-float-float-float}
Thêm đường cong Bezier bậc hai vào cuối đường


```python
def quadratic_bezier_to(self, x1, y1, x2, y2):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| x1 | **float** | Tọa độ X của điểm điều hướng |
| y1 | **float** | Tọa độ Y của điểm điều hướng |
| x2 | **float** | Tọa độ X của điểm cuối |
| y2 | **float** | Tọa độ Y của điểm cuối |


## quadratic_bezier_to(self, x1, y1, x2, y2, index) {#float-float-float-float-int}
Thêm đường cong Bezier bậc hai vào vị trí được chỉ định của đường


```python
def quadratic_bezier_to(self, x1, y1, x2, y2, index):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| x1 | **float** | Tọa độ X của điểm điều hướng |
| y1 | **float** | Tọa độ Y của điểm điều hướng |
| x2 | **float** | Tọa độ X của điểm cuối |
| y2 | **float** | Tọa độ Y của điểm cuối |
| index | **int** | Chỉ số của đoạn trong PathData |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Chỉ số đoạn vượt ra ngoài phạm vi PathData |



### Xem thêm
* lớp [`GeometryPath`](/slides/python-net/vi/aspose.slides/geometrypath)
* lớp [`PointF`](/slides/python-net/vi/aspose.slides/pointf)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)