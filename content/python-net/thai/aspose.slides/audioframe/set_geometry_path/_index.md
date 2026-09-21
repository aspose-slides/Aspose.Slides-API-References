---
title: set_geometry_path method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/audioframe/set_geometry_path/
weight: 80
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
อัปเดตเรขาคณิตของ shape จากอ็อบเจ็กต์ [`IGeometryPath`](/slides/python-net/th/aspose.slides/igeometrypath). พิกัดต้องอิงตามมุมซ้ายบนของ shape. เปลี่ยนประเภทของ shape ([`GeometryShape.shape_type`](/slides/python-net/th/aspose.slides/geometryshape/shape_type)) เป็น [`ShapeType.CUSTOM`](/slides/python-net/th/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_path(self, geometry_path):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| geometry_path | [`IGeometryPath`](/slides/python-net/th/aspose.slides/igeometrypath) | เส้นทางเรขาคณิต |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | ไม่พบเส้นทาง |
| **RuntimeError(Proxy error(ArgumentException))** | พบเส้นทางที่ว่าง |

### ดูเพิ่มเติม
* คลาส [`AudioFrame`](/slides/python-net/th/aspose.slides/audioframe)
* คลาส [`IGeometryPath`](/slides/python-net/th/aspose.slides/igeometrypath)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)