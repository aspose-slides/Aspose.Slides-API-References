---
title: check_password method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/presentationinfo/check_password/
weight: 10
---
## check_password(self, password) {#str}
ตรวจสอบว่ารหัสผ่านถูกต้องสำหรับการนำเสนอที่มีการป้องกันด้วยรหัสผ่านเปิดหรือไม่

### คืนค่า

True หากการนำเสนอถูกป้องกันด้วยรหัสผ่านเปิดและรหัสผ่านถูกต้องและ false ในกรณีอื่น

```python
def check_password(self, password):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| password | **str** | รหัสผ่านเพื่อทำการตรวจสอบ |

### หมายเหตุ

เมื่อรหัสผ่านเป็น None หรือว่างเปล่าเมธอดนี้คืนค่า false

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |
| **RuntimeError(Proxy error(NotSupportedException))** |  |

### ดูเพิ่มเติม
* คลาส [`PresentationInfo`](/slides/python-net/th/aspose.slides/presentationinfo)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)