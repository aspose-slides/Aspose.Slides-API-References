---
title: set_geometry_path method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/autoshape/set_geometry_path/
weight: 90
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
อัปเดตรูปทรงเรขาคณิตจากวัตถุ [`IGeometryPath`](/slides/python-net/th/aspose.slides/igeometrypath). พิกัดต้องสัมพันธ์กับมุมซ้าย
             บนของรูปทรง.
             เปลี่ยนประเภทของรูปทรง ([`GeometryShape.shape_type`](/slides/python-net/th/aspose.slides/geometryshape/shape_type)) เป็น [`ShapeType.CUSTOM`](/slides/python-net/th/aspose.slides/shapetype/CUSTOM).


```python
def set_geometry_path(self, geometry_path):
    ...
```


| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| geometry_path | [`IGeometryPath`](/slides/python-net/th/aspose.slides/igeometrypath) | เส้นทางเรขาคณิต |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | ไม่พบเส้นทาง |
| **RuntimeError(Proxy error(ArgumentException))** | พบเส้นทางว่าง |



### ดูเพิ่มเติม
* คลาส [`AutoShape`](/slides/python-net/th/aspose.slides/autoshape)
* คลาส [`IGeometryPath`](/slides/python-net/th/aspose.slides/igeometrypath)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)