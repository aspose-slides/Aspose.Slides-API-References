---
title: Is()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: 
type: docs
weight: 27
url: /th/system.io/details_endofstreamexception/is/
---
## Details_EndOfStreamException::Is(const System::TypeInfo\&) const method




```cpp
bool System::IO::Details_EndOfStreamException::Is(const System::TypeInfo &target) const override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) โครงสร้างที่อธิบายประเภทเพื่อทดสอบอ็อบเจกต์ปัจจุบัน |

### ค่ารีเทิร์น

True หากอ็อบเจกต์เป็นประเภทที่มีแท็กหรือคลาสย่อยของมัน, false ในกรณีอื่น

## หมายเหตุ

ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นการทำงานเช่นเดียวกับตัวดำเนินการ 'is' ของ C#.

## ดูเพิ่มเติม

* คลาส [TypeInfo](../../../system/typeinfo/)
* คลาส [Details_EndOfStreamException](../)
* เนมสเปซ [System::IO](../../)
* ไลบรารี [Aspose.Slides](../../../)