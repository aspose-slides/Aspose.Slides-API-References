---
title: Is()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: 
type: docs
weight: 27
url: /th/system/details_invalidcastexception/is/
---
## Details_InvalidCastException::Is(const System::TypeInfo\&) const เมธอด




```cpp
bool System::Details_InvalidCastException::Is(const System::TypeInfo &target) const override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) โครงสร้างที่อธิบายประเภทที่ใช้ทดสอบอ็อบเจ็กต์ปัจจุบัน |

### ค่าที่คืนกลับ

True หากอ็อบเจ็กต์เป็นประเภทที่มีแท็กหรือเป็นคลาสย่อยของมัน, false ในกรณีอื่น

## หมายเหตุ

ตรวจสอบว่าอ็อบเจ็กต์แสดงถึงอินสแตนซ์ของประเภทที่อธิบายโดย targetType. เป็นการทำงานคล้ายกับตัวดำเนินการ 'is' ของ C#

## ดูเพิ่มเติม

* คลาส [TypeInfo](../../typeinfo/)
* คลาส [Details_InvalidCastException](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)