---
title: Is()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: 
type: docs
weight: 27
url: /th/system/details_timeoutexception/is/
---
## Details_TimeoutException::Is(const System::TypeInfo\&) const method




```cpp
bool System::Details_TimeoutException::Is(const System::TypeInfo &target) const override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) โครงสร้างที่อธิบายประเภทเพื่อทดสอบอ็อบเจ็กต์ปัจจุบัน |

### ค่าที่ส่งคืน

True หากอ็อบเจ็กต์เป็นประเภทที่ตั้งค่าแท็กหรือคลาสย่อยของมัน, false มิฉะนั้น.
## หมายเหตุ

ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. เป็นการทำงานคล้ายกับออปอเรเตอร์ 'is' ของ C#.
## ดูเพิ่มเติม

* คลาส [TypeInfo](../../typeinfo/)
* คลาส [Details_TimeoutException](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)