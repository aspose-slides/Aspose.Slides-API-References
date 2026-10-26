---
title: Is()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: 
type: docs
weight: 27
url: /th/system/details_datamisalignedexception/is/
---
## รายละเอียด_DataMisalignedException::Is(const System::TypeInfo\&) const method




```cpp
bool System::Details_DataMisalignedException::Is(const System::TypeInfo &target) const override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) โครงสร้างที่อธิบายประเภทเพื่อทดสอบอ็อบเจกต์ปัจจุบัน |

### ค่าที่ส่งคืน

จริง หากอ็อบเจกต์เป็นประเภทที่มีแท็กหรือคลาสย่อยของมัน, มิฉะนั้นเป็นเท็จ.

## หมายเหตุ

ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นการทำงานคล้ายกับตัวดำเนินการ 'is' ของ C#.

## ดูเพิ่มเติม

* คลาส [TypeInfo](../../typeinfo/)
* คลาส [Details_DataMisalignedException](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)