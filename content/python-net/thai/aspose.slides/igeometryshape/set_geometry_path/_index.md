---
title: set_geometry_path method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/igeometryshape/set_geometry_path/
weight: 70
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
อัปเดตเรขาแบบของรูปร่างจากอ็อบเจกต์ [`IGeometryPath`](/slides/python-net/th/aspose.slides/igeometrypath). พิกัดต้องสัมพันธ์กับด้านซ้าย
             มุมบนของรูปร่าง.
             เปลี่ยนประเภทของรูปร่าง ([`IGeometryShape.shape_type`](/slides/python-net/th/aspose.slides/igeometryshape/shape_type)) เป็น [`ShapeType.CUSTOM`](/slides/python-net/th/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_path(self, geometry_path):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| geometry_path | [`IGeometryPath`](/slides/python-net/th/aspose.slides/igeometrypath) | Geometry path |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | ไม่พบเส้นทาง |
| **RuntimeError(Proxy error(ArgumentException))** | พบเส้นทางว่าง |



### ดูเพิ่มเติม
* คลาส [`IGeometryPath`](/slides/python-net/th/aspose.slides/igeometrypath)
* คลาส [`IGeometryShape`](/slides/python-net/th/aspose.slides/igeometryshape)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)