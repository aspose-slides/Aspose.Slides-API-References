---
title: Is()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: 
type: docs
weight: 27
url: /th/system/details_nullreferenceexception/is/
---
## Details_NullReferenceException::Is(const System::TypeInfo\&) const เมธอด




```cpp
bool System::Details_NullReferenceException::Is(const System::TypeInfo &target) const override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) โครงสร้างที่อธิบายประเภทเพื่อทดสอบวัตถุปัจจุบันต่อ |

### ค่าที่ส่งคืน

True หากวัตถุเป็นประเภทที่มีแท็กหรือคลาสย่อยของมัน, false มิฉะนั้น.

## หมายเหตุ

ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นการทำงานที่คล้ายกับตัวดำเนินการ 'is' ของ C#.

## ดูเพิ่มเติม

* คลาส [TypeInfo](../../typeinfo/)
* คลาส [Details_NullReferenceException](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)