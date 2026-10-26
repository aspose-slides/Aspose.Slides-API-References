---
title: Is()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: 
type: docs
weight: 27
url: /th/system/details_argumentexception/is/
---
## Details_ArgumentException::Is(const System::TypeInfo\&) const method




```cpp
bool System::Details_ArgumentException::Is(const System::TypeInfo &target) const override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) โครงสร้างที่อธิบายประเภทที่ใช้ทดสอบวัตถุปัจจุบัน |

### ค่าที่ส่งคืน

True หากวัตถุเป็นประเภทที่แท็กไว้หรือเป็นคลาสย่อยของมัน, false ในกรณีอื่น.
## หมายเหตุ

ตรวจสอบว่าวัตถุแสดงถึงอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นการทำงานที่คล้ายกับตัวดำเนินการ 'is' ของ C#.
## ดูเพิ่มเติม

* คลาส [TypeInfo](../../typeinfo/)
* คลาส [Details_ArgumentException](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)