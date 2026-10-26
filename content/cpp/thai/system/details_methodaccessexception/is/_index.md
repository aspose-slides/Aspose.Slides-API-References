---
title: Is()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: 
type: docs
weight: 27
url: /th/system/details_methodaccessexception/is/
---
## รายละเอียด_MethodAccessException::Is(const System::TypeInfo\&) const method

```cpp
bool System::Details_MethodAccessException::Is(const System::TypeInfo &target) const override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) โครงสร้างที่อธิบายประเภทเพื่อทดสอบอ็อบเจ็กต์ปัจจุบันกับ |

### ค่ารีเทิร์น

คืนค่า true หากอ็อบเจ็กต์เป็นประเภทที่ถูกแท็กหรือคลาสย่อยของมัน, มิฉะนั้นคืนค่า false.

## หมายเหตุ

ตรวจสอบว่ามีอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. ตรงกันกับตัวดำเนินการ 'is' ของ C#.

## ดูเพิ่มเติม

* คลาส [TypeInfo](../../typeinfo/)
* คลาส [Details_MethodAccessException](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)