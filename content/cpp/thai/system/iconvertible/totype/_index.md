---
title: ToType()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "แปลงค่าของอ็อบเจกต์นี้เป็น System::Object ของ System::Type ที่ระบุซึ่งมีค่าเทียบเท่า โดยใช้ข้อมูลการจัดรูปแบบตามวัฒนธรรมที่ระบุ"
type: docs
weight: 209
url: /th/system/iconvertible/totype/
---
## IConvertible::ToType(const TypeInfo\&, System::SharedPtr\<System::IFormatProvider\>) เมธอด

แปลงค่าของอ็อบเจกต์นี้เป็น [System::Object](../../object/) ของ System::Type ที่ระบุซึ่งมีค่าที่เทียบเท่า โดยใช้ข้อมูลการจัดรูปแบบตามวัฒนธรรมที่ระบุ

```cpp
virtual System::SharedPtr<System::Object> System::IConvertible::ToType(const TypeInfo &conversionType, System::SharedPtr<System::IFormatProvider> provider)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| conversionType | const [TypeInfo](../../typeinfo/)\& | System::Type ที่ค่าของอ็อบเจกต์นี้ถูกแปลงเป็น |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | การทำงานของอินเทอร์เฟซ [System::IFormatProvider](../../iformatprovider/) ที่ให้ข้อมูลการจัดรูปแบบตามวัฒนธรรม |

### ค่าที่ส่งกลับ

[System::Object](../../object/) อินสแตนซ์ของประเภท conversionType ที่ค่าของมันเทียบเท่ากับค่าของอ็อบเจกต์นี้

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../sharedptr/)
* คลาส [Object](../../object/)
* คลาส [TypeInfo](../../typeinfo/)
* คลาส [IFormatProvider](../../iformatprovider/)
* คลาส [IConvertible](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)