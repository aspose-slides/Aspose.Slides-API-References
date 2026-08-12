---
title: Is()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: 
type: docs
weight: 27
url: /th/system/details_formatexception/is/
---
## Details_FormatException::Is(const System::TypeInfo\&) const method




```cpp
bool System::Details_FormatException::Is(const System::TypeInfo &target) const override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) โครงสร้างที่อธิบายประเภทเพื่อทดสอบวัตถุปัจจุบัน |

### ค่าที่คืน

จริงหากวัตถุเป็นประเภทที่กำหนดหรือเป็นคลาสย่อยของมัน, เท็จในกรณีอื่น

## หมายเหตุ

ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เทียบเคียงกับตัวดำเนินการ 'is' ของ C#.

## ดูเพิ่มเติม

* คลาส [TypeInfo](../../typeinfo/)
* คลาส [Details_FormatException](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)