---
title: check_write_protection method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/ipresentationinfo/check_write_protection/
weight: 20
---
## check_write_protection(self, password) {#str}
ตรวจสอบว่ารหัสผ่านสำหรับการแก้ไขนั้นถูกต้องสำหรับการนำเสนอที่มีการป้องกันการเขียนหรือไม่

### ผลลัพธ์
True หากการนำเสนอถูกป้องกันการเขียนและรหัสผ่านถูกต้อง หากไม่เป็นเช่นนั้นจะคืนค่า False.



```python
def check_write_protection(self, password):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| password | **str** | รหัสผ่านที่ต้องการตรวจสอบ. |

### หมายเหตุ
1. คุณควรตรวจสอบคุณสมบัติ [`IPresentationInfo.is_write_protected`](/slides/python-net/th/aspose.slides/ipresentationinfo/is_write_protected) ก่อนเรียกใช้เมธอดนี้.
2. เมื่อรหัสผ่านเป็น None หรือว่างเปล่า เมธอดนี้จะคืนค่า false.

### ข้อยกเว้น
| Exception | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |

### ดูเพิ่มเติม
* คลาส [`IPresentationInfo`](/slides/python-net/th/aspose.slides/ipresentationinfo)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)