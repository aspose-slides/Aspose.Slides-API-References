---
title: set_geometry_paths method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/autoshape/set_geometry_paths/
weight: 100
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
Cập nhật hình học của shape từ mảng [`IGeometryPath`](/slides/python-net/vi/aspose.slides/igeometrypath). Tọa độ phải tương đối với góc trái trên của shape.
Thay đổi loại của shape ([`GeometryShape.shape_type`](/slides/python-net/vi/aspose.slides/geometryshape/shape_type)) thành [`ShapeType.CUSTOM`](/slides/python-net/vi/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_paths(self, geometry_paths):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | Mảng đường dẫn hình học |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Không tìm thấy đường dẫn |
| **RuntimeError(Proxy error(ArgumentException))** | Đường dẫn rỗng |

### Xem thêm
* lớp [`AutoShape`](/slides/python-net/vi/aspose.slides/autoshape)
* lớp [`IGeometryPath`](/slides/python-net/vi/aspose.slides/igeometrypath)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)