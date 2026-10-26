---
title: ToChar()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: แปลงค่าของอินสแตนซ์นี้เป็นอักขระ Unicode ที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบที่เฉพาะเจาะจงตามวัฒนธรรมที่ระบุ
type: docs
weight: 27
url: /th/system/iconvertible/tochar/
---
## IConvertible::ToChar(System::SharedPtr\<System::IFormatProvider\>) เมธอด


Converts the value of this instance to an equivalent Unicode character using the specified culture-specific formatting information.

```cpp
virtual char_t System::IConvertible::ToChar(System::SharedPtr<System::IFormatProvider> provider)=0
```


### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | การนำไปใช้ของอินเทอร์เฟซ [System::IFormatProvider](../../iformatprovider/) ที่จัดหาข้อมูลการฟอร์แมตตามวัฒนธรรม. |

### ค่าที่ส่งคืน

อักขระ Unicode ที่เทียบเท่ากับค่าของอินสแตนซ์นี้.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../sharedptr/)
* คลาส [IFormatProvider](../../iformatprovider/)
* คลาส [IConvertible](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)