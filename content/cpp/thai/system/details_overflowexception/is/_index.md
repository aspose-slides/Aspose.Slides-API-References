---
title: Is()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: 
type: docs
weight: 27
url: /th/system/details_overflowexception/is/
---
## รายละเอียด_OverflowException::Is(const System::TypeInfo\&) const method




```cpp
bool System::Details_OverflowException::Is(const System::TypeInfo &target) const override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) โครงสร้างที่อธิบายประเภทเพื่อทดสอบวัตถุปัจจุบันต่อ |

### ค่าที่ส่งกลับ

True หากวัตถุเป็นประเภทที่ทำเครื่องหมายหรือเป็นคลาสย่อยของมัน, false ในกรณีอื่น

## หมายเหตุ

ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นเทียบเคียงของตัวดำเนินการ 'is' ของ C#.

## ดูเพิ่มเติม

* คลาส [TypeInfo](../../typeinfo/)
* คลาส [Details_OverflowException](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)