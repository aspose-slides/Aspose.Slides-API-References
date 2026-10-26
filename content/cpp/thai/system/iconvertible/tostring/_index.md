---
title: ToString()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "แปลงค่าของอินสแตนซ์นี้เป็น System::String ที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบตามวัฒนธรรมที่ระบุ"
type: docs
weight: 196
url: /th/system/iconvertible/tostring/
---
## IConvertible::ToString(System::SharedPtr\<System::IFormatProvider\>) method


แปลงค่าของอินสแตนซ์นี้เป็น [System::String](../../string/) ที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบตามวัฒนธรรมที่ระบุ

```cpp
virtual System::String System::IConvertible::ToString(System::SharedPtr<System::IFormatProvider> provider)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | การทำงานของอินเทอร์เฟซ [System::IFormatProvider](../../iformatprovider/) ที่จัดหาข้อมูลการจัดรูปแบบตามวัฒนธรรม |

### ค่าที่ส่งกลับ

อินสแตนซ์ [System::String](../../string/) ที่เทียบเท่ากับค่าของอินสแตนซ์นี้

## IConvertible::ToString() const method


คล้ายกับเมธอด [Object.ToString()](../../object/tostring/) ของ C#. ให้ความสามารถในการแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง

```cpp
virtual String System::Object::ToString() const
```


### ค่าที่ส่งกลับ

การแสดงผล [String](../../string/) ตามที่คลาสสุดท้ายให้มา

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../sharedptr/)
* คลาส [String](../../string/)
* คลาส [IFormatProvider](../../iformatprovider/)
* คลาส [IConvertible](../)
* เนมสเปซ [System](../../)
* Library [Aspose.Slides](../../../)