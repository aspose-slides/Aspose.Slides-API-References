---
title: quadratic_bezier_to method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/geometrypath/quadratic_bezier_to/
weight: 70
---
## quadratic_bezier_to(self, point1, point2) {#asposepydrawingpointf-asposepydrawingpointf}
Thêm đường cong Bézier bậc hai tại cuối đường dẫn

```python
def quadratic_bezier_to(self, point1, point2):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Điểm điều hướng |
| point2 | **aspose.slides.PointF** | Điểm cuối |

## quadratic_bezier_to(self, point1, point2, index) {#asposepydrawingpointf-asposepydrawingpointf-int}
Thêm đường cong Bézier bậc hai vào vị trí chỉ định của đường dẫn

```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Điểm điều hướng |
| point2 | **aspose.slides.PointF** | Điểm cuối |
| index | **int** | Chỉ số của đoạn trong PathData |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Chỉ số đoạn nằm ngoài phạm vi PathData |

## quadratic_bezier_to(self, x1, y1, x2, y2) {#float-float-float-float}
Thêm đường cong Bézier bậc hai tại cuối đường dẫn

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
Thêm đường cong Bézier bậc hai vào vị trí chỉ định của đường dẫn

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
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Chỉ số đoạn nằm ngoài phạm vi PathData |

### Xem thêm
* lớp [`GeometryPath`](/slides/python-net/vi/aspose.slides/geometrypath)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)