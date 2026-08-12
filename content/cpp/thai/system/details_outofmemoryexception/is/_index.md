---
title: Is()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: 
type: docs
weight: 27
url: /th/system/details_outofmemoryexception/is/
---
## Details_OutOfMemoryException::Is(const System::TypeInfo\&) const method

```cpp
bool System::Details_OutOfMemoryException::Is(const System::TypeInfo &target) const override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) โครงสร้างที่อธิบายประเภทที่ใช้ทดสอบอ็อบเจ็กต์ปัจจุบัน |

### Return Value

คืนค่า true หากอ็อบเจ็กต์เป็นประเภทที่ทำเครื่องหมายหรือเป็นคลาสย่อยของมัน, มิฉะนั้นคืนค่า false.

## หมายเหตุ

ตรวจสอบว่าตัวอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. คล้ายกับตัวดำเนินการ 'is' ของ C#.

## ดูเพิ่มเติม

* คลาส [TypeInfo](../../typeinfo/)
* คลาส [Details_OutOfMemoryException](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)