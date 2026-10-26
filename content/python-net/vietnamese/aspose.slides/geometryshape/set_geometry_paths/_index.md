---
title: set_geometry_paths method
second_title: Aspose.Slides cho Python qua API .NET
description: 
type: docs
url: /vi/aspose.slides/geometryshape/set_geometry_paths/
weight: 90
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
Cập nhật hình học của shape từ mảng của [`IGeometryPath`](/slides/python-net/vi/aspose.slides/igeometrypath). Các tọa độ phải tương đối so với góc trái trên của shape. Thay đổi loại của shape ([`GeometryShape.shape_type`](/slides/python-net/vi/aspose.slides/geometryshape/shape_type)) thành [`ShapeType.CUSTOM`](/slides/python-net/vi/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_paths(self, geometry_paths):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | Mảng các đường hình học |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Không tìm thấy đường |
| **RuntimeError(Proxy error(ArgumentException))** | Đường rỗng |

### Xem thêm
* lớp [`GeometryShape`](/slides/python-net/vi/aspose.slides/geometryshape)
* lớp [`IGeometryPath`](/slides/python-net/vi/aspose.slides/igeometrypath)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)