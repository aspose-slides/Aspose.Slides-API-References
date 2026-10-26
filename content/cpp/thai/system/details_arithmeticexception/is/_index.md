---
title: Is()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: 
type: docs
weight: 27
url: /th/system/details_arithmeticexception/is/
---
## Details_ArithmeticException::Is(const System::TypeInfo\&) const method




```cpp
bool System::Details_ArithmeticException::Is(const System::TypeInfo &target) const override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) โครงสร้างที่อธิบายประเภทเพื่อทดสอบวัตถุปัจจุบันกับ |

### ค่าที่ส่งกลับ

True หากวัตถุเป็นประเภทที่ระบุหรือเป็นคลาสย่อยของมัน, false ในกรณีอื่น.

## หมายเหตุ

ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นการทำงานที่คล้ายกับตัวดำเนินการ 'is' ของ C#.

## ดูเพิ่มเติม

* คลาส [TypeInfo](../../typeinfo/)
* คลาส [Details_ArithmeticException](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)