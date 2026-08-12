---
title: Is()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: 
type: docs
weight: 27
url: /th/system.io/details_fileloadexception/is/
---
## Details_FileLoadException::Is(const System::TypeInfo\&) const method




```cpp
bool System::IO::Details_FileLoadException::Is(const System::TypeInfo &target) const override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) โครงสร้างที่อธิบายประเภทที่ต้องทดสอบอ็อบเจ็กต์ปัจจุบัน |

### ผลลัพธ์

True if object is of tagged type or its subclass, false otherwise.

## หมายเหตุ

ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. Analog of C# 'is' operator. 

## ดูเพิ่มเติม

* Class [TypeInfo](../../../system/typeinfo/)
* Class [Details_FileLoadException](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)