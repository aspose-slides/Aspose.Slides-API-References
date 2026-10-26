---
title: Is()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: 
type: docs
weight: 27
url: /th/system/details_invalidprogramexception/is/
---
## Details_InvalidProgramException::Is(const System::TypeInfo\&) const method

```cpp
bool System::Details_InvalidProgramException::Is(const System::TypeInfo &target) const override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) โครงสร้างที่อธิบายประเภทเพื่อทดสอบอ็อบเจกต์ปัจจุบันต่อ |

### ค่าที่ส่งกลับ

True หากอ็อบเจกต์เป็นประเภทที่ทำเครื่องหมายหรือเป็นคลาสย่อยของมัน, false ในกรณีอื่น.

## หมายเหตุ

ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นเช่นเดียวกับตัวดำเนินการ 'is' ของ C#.

## ดูเพิ่มเติม

* คลาส [TypeInfo](../../typeinfo/)
* คลาส [Details_InvalidProgramException](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)