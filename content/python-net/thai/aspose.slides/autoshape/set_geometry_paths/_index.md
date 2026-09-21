---
title: set_geometry_paths method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/autoshape/set_geometry_paths/
weight: 100
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
อัปเดตเรขาคณิตของรูปร่างจากอาเรย์ของ [`IGeometryPath`](/slides/python-net/th/aspose.slides/igeometrypath). พิกัดต้องสัมพันธ์กับมุมซ้ายบนของรูปร่าง. เปลี่ยนประเภทของรูปร่าง ([`GeometryShape.shape_type`](/slides/python-net/th/aspose.slides/geometryshape/shape_type)) เป็น [`ShapeType.CUSTOM`](/slides/python-net/th/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_paths(self, geometry_paths):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | อาเรย์ของเส้นทางเรขาคณิต |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | ไม่พบเส้นทาง |
| **RuntimeError(Proxy error(ArgumentException))** | เส้นทางว่าง |



### ดูเพิ่มเติม
* คลาส [`AutoShape`](/slides/python-net/th/aspose.slides/autoshape)
* คลาส [`IGeometryPath`](/slides/python-net/th/aspose.slides/igeometrypath)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)