---
title: quadratic_bezier_to method
second_title: Tham khảo API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides/igeometrypath/quadratic_bezier_to/
weight: 60
---
## quadratic_bezier_to(self, point1, point2) {#asposeslidespointf-asposeslidespointf}
Thêm đường cong Bezier bậc hai vào cuối đường dẫn


```python
def quadratic_bezier_to(self, point1, point2):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/vi/aspose.slides/pointf) | Điểm hướng |
| point2 | [`PointF`](/slides/python-net/vi/aspose.slides/pointf) | Điểm cuối |


## quadratic_bezier_to(self, point1, point2, index) {#asposeslidespointf-asposeslidespointf-int}
Thêm đường cong Bezier bậc hai vào vị trí được chỉ định của đường dẫn


```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/vi/aspose.slides/pointf) | Điểm hướng |
| point2 | [`PointF`](/slides/python-net/vi/aspose.slides/pointf) | Điểm cuối |
| index | **int** | Chỉ mục của đoạn trong PathData |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Chỉ mục đoạn vượt quá phạm vi PathData |

## quadratic_bezier_to(self, x1, y1, x2, y2) {#float-float-float-float}
Thêm đường cong Bezier bậc hai vào cuối đường dẫn


```python
def quadratic_bezier_to(self, x1, y1, x2, y2):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| x1 | **float** | tọa độ X của điểm hướng |
| y1 | **float** | tọa độ Y của điểm hướng |
| x2 | **float** | tọa độ X của điểm cuối |
| y2 | **float** | tọa độ Y của điểm cuối |


## quadratic_bezier_to(self, x1, y1, x2, y2, index) {#float-float-float-float-int}
Thêm đường cong Bezier bậc hai vào vị trí được chỉ định của đường dẫn


```python
def quadratic_bezier_to(self, x1, y1, x2, y2, index):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| x1 | **float** | tọa độ X của điểm hướng |
| y1 | **float** | tọa độ Y của điểm hướng |
| x2 | **float** | tọa độ X của điểm cuối |
| y2 | **float** | tọa độ Y của điểm cuối |
| index | **int** | Chỉ mục của đoạn trong PathData |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Chỉ mục đoạn vượt quá phạm vi PathData |



### Xem Thêm
* lớp [`IGeometryPath`](/slides/python-net/vi/aspose.slides/igeometrypath)
* lớp [`PointF`](/slides/python-net/vi/aspose.slides/pointf)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)