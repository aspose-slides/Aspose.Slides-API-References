---
title: Is()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: 
type: docs
weight: 27
url: /th/system.threading/details_threadinterruptedexception/is/
---
## Details_ThreadInterruptedException::Is(const System::TypeInfo\&) const เมธอด




```cpp
bool System::Threading::Details_ThreadInterruptedException::Is(const System::TypeInfo &target) const override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) โครงสร้างที่อธิบายประเภทเพื่อทดสอบอ็อบเจ็กต์ปัจจุบันกับ. |

### ค่าที่ส่งกลับ

จริงถ้าอ็อบเจ็กต์เป็นประเภทที่กำหนดหรือเป็นคลาสย่อยของมัน, เท็จในกรณีอื่น.
## หมายเหตุ


ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. คล้ายกับตัวดำเนินการ 'is' ของ C#.
## ดูเพิ่มเติม

* คลาส [TypeInfo](../../../system/typeinfo/)
* คลาส [Details_ThreadInterruptedException](../)
* เนมสเปซ [System::Threading](../../)
* ไลบรารี [Aspose.Slides](../../../)