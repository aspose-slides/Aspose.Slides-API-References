---
title: set_geometry_paths method
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides/connector/set_geometry_paths/
weight: 100
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
Cập nhật hình học của hình từ mảng [`IGeometryPath`](/slides/python-net/vi/aspose.slides/igeometrypath). Các tọa độ phải tương đối so với góc trái trên của hình. Thay đổi loại của hình ([`GeometryShape.shape_type`](/slides/python-net/vi/aspose.slides/geometryshape/shape_type)) thành [`ShapeType.CUSTOM`](/slides/python-net/vi/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_paths(self, geometry_paths):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | Array geometry paths |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | No path found |
| **RuntimeError(Proxy error(ArgumentException))** | Empty path |

### Xem thêm
* lớp [`Connector`](/slides/python-net/vi/aspose.slides/connector)
* lớp [`IGeometryPath`](/slides/python-net/vi/aspose.slides/igeometrypath)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)