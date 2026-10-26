---
title: Is()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: 
type: docs
weight: 27
url: /th/system/details_stackoverflowexception/is/
---
## Details_StackOverflowException::Is(const System::TypeInfo\&) const method




```cpp
bool System::Details_StackOverflowException::Is(const System::TypeInfo &target) const override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) โครงสร้างที่อธิบายประเภทเพื่อทดสอบวัตถุปัจจุบันเทียบกับ |

### ค่าที่ส่งกลับ

True หากวัตถุเป็นประเภทที่ทำเครื่องหมายหรือเป็นคลาสย่อยของประเภทนั้น, false ในกรณีอื่น.

## หมายเหตุ

ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นการเทียบกับตัวดำเนินการ 'is' ของ C#.

## ดูเพิ่มเติม

* คลาส [TypeInfo](../../typeinfo/)
* คลาส [Details_StackOverflowException](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)