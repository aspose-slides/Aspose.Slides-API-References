---
title: Is()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: 
type: docs
weight: 27
url: /th/system/details_systemexception/is/
---
## รายละเอียด_SystemException::Is(const System::TypeInfo\&) const method

```cpp
bool System::Details_SystemException::Is(const System::TypeInfo &target) const override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) โครงสร้างที่อธิบายประเภทเพื่อทดสอบวัตถุปัจจุบันกับ |

### ค่าที่คืน

true หากวัตถุเป็นประเภทที่มีแท็กหรือเป็นคลาสย่อยของมัน, false ในกรณีอื่น

## หมายเหตุ

ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นการทำงานคล้ายกับตัวดำเนินการ 'is' ของ C#.

## ดูเพิ่มเติม

* คลาส [TypeInfo](../../typeinfo/)
* คลาส [Details_SystemException](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)