---
title: set_geometry_paths method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.smartart/smartartshape/set_geometry_paths/
weight: 90
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
อัปเดตรูปทรงของ shape จากอาร์เรย์ของ [`IGeometryPath`](/slides/python-net/th/aspose.slides/igeometrypath). พิกัดต้องสัมพันธ์กับมุมซ้าย
             บนของ shape.
             เปลี่ยนประเภทของ shape ([`GeometryShape.shape_type`](/slides/python-net/th/aspose.slides/geometryshape/shape_type)) เป็น [`ShapeType.CUSTOM`](/slides/python-net/th/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_paths(self, geometry_paths):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | อาร์เรย์ของ geometry paths |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | ไม่พบเส้นทาง |
| **RuntimeError(Proxy error(ArgumentException))** | เส้นทางว่าง |



### ดูเพิ่มเติม
* คลาส [`IGeometryPath`](/slides/python-net/th/aspose.slides/igeometrypath)
* คลาส [`SmartArtShape`](/slides/python-net/th/aspose.slides.smartart/smartartshape)
* โมดูล [`aspose.slides.smartart`](/slides/python-net/th/aspose.slides.smartart)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)