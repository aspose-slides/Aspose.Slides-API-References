---
title: Is()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: 
type: docs
weight: 27
url: /th/system/details_notimplementedexception/is/
---
## รายละเอียด_NotImplementedException::Is(const System::TypeInfo\&) const method

```cpp
bool System::Details_NotImplementedException::Is(const System::TypeInfo &target) const override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) structure describing the type to test current object against. |

### ค่าที่คืน

True หากอ็อบเจ็กต์เป็นประเภทที่มีแท็กหรือคลาสย่อยของมัน, false ในกรณีอื่น.

## หมายเหตุ

ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. คล้ายกับตัวดำเนินการ 'is' ของ C#.

## ดูเพิ่มเติม

* คลาส [TypeInfo](../../typeinfo/)
* คลาส [Details_NotImplementedException](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)