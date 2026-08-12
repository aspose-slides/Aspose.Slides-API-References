---
title: Format()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ส่งคืนการแสดงผลเป็นสตริงของค่าที่แสดงโดยออบเจ็กต์ปัจจุบันโดยใช้รูปแบบที่ระบุ
type: docs
weight: 1
url: /th/system/icustomformatter/format/
---
## ICustomFormatter::Format(System::String, System::SharedPtr\<System::Object\>, System::SharedPtr\<System::IFormatProvider\>) เมธอด

ส่งคืนการแสดงผลเป็นสตริงของค่าที่แสดงโดยออบเจ็กต์ปัจจุบันโดยใช้รูปแบบที่ระบุ

```cpp
virtual System::String System::ICustomFormatter::Format(System::String format, System::SharedPtr<System::Object> arg, System::SharedPtr<System::IFormatProvider> formatProvider)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| format | [System::String](../../string/) | รูปแบบสตริง |
| arg | [System::SharedPtr](../../sharedptr/)\<[System::Object](../../object/)\> | ออบเจ็กต์ที่ต้องการจัดรูปแบบ |
| formatProvider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | ออบเจ็กต์ที่ให้ข้อมูลการจัดรูปแบบ |

### ค่าที่ส่งคืน

การแสดงผลเป็นสตริงของ **arg** ที่จัดรูปแบบตามรูปแบบที่ระบุโดย **format** และ **formatProvider**

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../sharedptr/)
* คลาส [String](../../string/)
* คลาส [Object](../../object/)
* คลาส [IFormatProvider](../../iformatprovider/)
* คลาส [ICustomFormatter](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)