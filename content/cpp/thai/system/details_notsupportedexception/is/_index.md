---
title: Is()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: 
type: docs
weight: 27
url: /th/system/details_notsupportedexception/is/
---
## Details_NotSupportedException::Is(const System::TypeInfo\&) const method

```cpp
bool System::Details_NotSupportedException::Is(const System::TypeInfo &target) const override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) โครงสร้างที่อธิบายประเภทเพื่อทดสอบอ็อบเจ็กต์ปัจจุบันกับ. |

### ค่าที่คืน

คืนค่า true หากอ็อบเจ็กต์เป็นประเภทที่ทำเครื่องหมายหรือคลาสย่อยของมัน, มิฉะนั้นคืนค่า false.

## หมายเหตุ

Check if object represents an instance of type described by targetType. Analog of C# 'is' operator.

## ดูเพิ่มเติม

* คลาส [TypeInfo](../../typeinfo/)
* คลาส [Details_NotSupportedException](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)