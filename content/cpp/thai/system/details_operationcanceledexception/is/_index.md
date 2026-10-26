---
title: Is()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: 
type: docs
weight: 27
url: /th/system/details_operationcanceledexception/is/
---
## รายละเอียด_OperationCanceledException::Is(const System::TypeInfo\&) const method

```cpp
bool System::Details_OperationCanceledException::Is(const System::TypeInfo &target) const override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) โครงสร้างที่อธิบายประเภทที่จะทดสอบวัตถุปัจจุบันกับ |

### ค่าที่คืน

True หากวัตถุเป็นประเภทที่ทำเครื่องหมายหรือคลาสย่อยของมัน, false ในกรณีอื่น.

## หมายเหตุ

ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นแนวคิดคล้ายกับตัวดำเนินการ 'is' ของ C#.

## ดูเพิ่มเติม

* คลาส [TypeInfo](../../typeinfo/)
* คลาส [Details_OperationCanceledException](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)