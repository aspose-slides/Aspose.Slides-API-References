---
title: check_write_protection method
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Python ผ่าน .NET
description: 
type: docs
url: /th/aspose.slides/presentationinfo/check_write_protection/
weight: 20
---
## check_write_protection(self, password) {#str}
ตรวจสอบว่ารหัสผ่านสำหรับการแก้ไขนั้นถูกต้องสำหรับการนำเสนอที่มีการป้องกันการเขียนหรือไม่.

### คืนค่า

True หากการนำเสนอถูกป้องกันการเขียนและรหัสผ่านถูกต้อง มิฉะนั้นเป็น False.



```python
def check_write_protection(self, password):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| password | **str** | รหัสผ่านที่จะตรวจสอบ. |

### หมายเหตุ

1. คุณควรตรวจสอบคุณสมบัติ [`PresentationInfo.is_write_protected`](/slides/python-net/th/aspose.slides/presentationinfo/is_write_protected) ก่อนเรียกใช้เมธอดนี้.
2. เมื่อ password เป็น None หรือว่างเปล่า เมธอดนี้จะคืนค่า false.

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |



### ดูเพิ่มเติม
* คลาส [`PresentationInfo`](/slides/python-net/th/aspose.slides/presentationinfo)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)