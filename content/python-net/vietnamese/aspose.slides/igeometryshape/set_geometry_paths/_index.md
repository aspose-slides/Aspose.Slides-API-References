---
title: set_geometry_paths method
second_title: Tài liệu tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/igeometryshape/set_geometry_paths/
weight: 80
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
Cập nhật hình học của hình dạng từ mảng [`IGeometryPath`](/slides/python-net/vi/aspose.slides/igeometrypath). Các tọa độ phải tương đối so với bên trái
             góc trên của hình dạng.
Thay đổi loại của hình dạng ([`IGeometryShape.shape_type`](/slides/python-net/vi/aspose.slides/igeometryshape/shape_type)) thành [`ShapeType.CUSTOM`](/slides/python-net/vi/aspose.slides/shapetype/CUSTOM).



```python
def set_geometry_paths(self, geometry_paths):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | Mảng các đường geometry |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Không tìm thấy đường dẫn |
| **RuntimeError(Proxy error(ArgumentException))** | Đường dẫn rỗng |



### Xem thêm
* lớp [`IGeometryPath`](/slides/python-net/vi/aspose.slides/igeometrypath)
* lớp [`IGeometryShape`](/slides/python-net/vi/aspose.slides/igeometryshape)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)