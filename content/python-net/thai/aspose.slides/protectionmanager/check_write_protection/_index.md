---
title: check_write_protection method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/protectionmanager/check_write_protection/
weight: 10
---
## check_write_protection(self, password) {#str}
กำหนดว่าการนำเสนอถูกป้องกันด้วยรหัสผ่านเพื่อการแก้ไขหรือไม่

### ผลลัพธ์

True หากรหัสผ่านถูกต้อง; หากไม่ใช่, false.



```python
def check_write_protection(self, password):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| password | **str** | รหัสผ่านสำหรับตรวจสอบ |

### หมายเหตุ

1. คุณควรตรวจสอบคุณสมบัติ [`ProtectionManager.is_write_protected`](/slides/python-net/th/aspose.slides/protectionmanager/is_write_protected) ก่อนเรียกใช้เมธอดนี้
2. เมื่อรหัสผ่านเป็น None หรือว่างเปล่า เมธอดนี้จะคืนค่า false

### ดูเพิ่มเติม
* คลาส [`ProtectionManager`](/slides/python-net/th/aspose.slides/protectionmanager)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)