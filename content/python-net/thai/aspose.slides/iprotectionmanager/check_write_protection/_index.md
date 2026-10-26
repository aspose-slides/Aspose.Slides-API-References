---
title: check_write_protection method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/iprotectionmanager/check_write_protection/
weight: 10
---
## check_write_protection(self, password) {#str}
กำหนดว่าการนำเสนอได้รับการป้องกันด้วยรหัสผ่านเพื่อการแก้ไขหรือไม่

### ผลลัพธ์

True ถ้ารหัสผ่านเป็นค่าที่ถูกต้อง; หากไม่เป็นเช่นนั้น จะเป็น false.



```python
def check_write_protection(self, password):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| password | **str** | รหัสผ่านสำหรับการตรวจสอบ. |

### หมายเหตุ

1. คุณควรตรวจสอบ property [`IProtectionManager.is_write_protected`](/slides/python-net/th/aspose.slides/iprotectionmanager/is_write_protected) ก่อนเรียกใช้เมธอดนี้.
2. เมื่อรหัสผ่านเป็น None หรือว่างเปล่า เมธอดนี้จะคืนค่า false.



### ดูเพิ่ม
* คลาส [`IProtectionManager`](/slides/python-net/th/aspose.slides/iprotectionmanager)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)