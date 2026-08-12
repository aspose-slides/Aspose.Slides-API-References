---
title: AddText()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: เพิ่มข้อความธรรมดาไปยังไฟล์ html โดยแทนที่อักขระพิเศษด้วย entity ของ html. การขึ้นบรรทัดและช่องว่างจะไม่ถูกแทนที่.
type: docs
weight: 92
url: /th/aspose.slides.export/ihtmlgenerator/addtext/
---
## IHtmlGenerator::AddText(System::String) เมธอด

เพิ่มข้อความธรรมดาไปยังไฟล์ html โดยแทนที่อักขระพิเศษด้วย html entities. การขึ้นบรรทัดและช่องว่างจะไม่ถูกแทนที่.

```cpp
virtual void Aspose::Slides::Export::IHtmlGenerator::AddText(System::String text)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | ข้อความที่จะเพิ่ม. |

## IHtmlGenerator::AddText(System::ArrayPtr\<char16_t\>) เมธอด

เพิ่มข้อความธรรมดาไปยังไฟล์ html โดยแทนที่อักขระพิเศษด้วย html entities. การขึ้นบรรทัดและช่องว่างจะไม่ถูกแทนที่.

```cpp
virtual void Aspose::Slides::Export::IHtmlGenerator::AddText(System::ArrayPtr<char16_t> text)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | [System::ArrayPtr](../../../system/arrayptr/)\<char16_t\> | ข้อความที่จะเพิ่ม. |

## IHtmlGenerator::AddText(System::ArrayPtr\<char16_t\>, int32_t, int32_t) เมธอด

เพิ่มข้อความธรรมดาไปยังไฟล์ html โดยแทนที่อักขระพิเศษด้วย html entities. การขึ้นบรรทัดและช่องว่างจะไม่ถูกแทนที่.

```cpp
virtual void Aspose::Slides::Export::IHtmlGenerator::AddText(System::ArrayPtr<char16_t> text, int32_t startIndex, int32_t length)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| text | [System::ArrayPtr](../../../system/arrayptr/)\<char16_t\> | ข้อความที่จะเพิ่ม. |
| startIndex | **int32_t** | ดัชนีเริ่มต้นของส่วนที่จะเพิ่ม. |
| length | **int32_t** | ความยาวของส่วนที่จะเพิ่ม. |

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [String](../../../system/string/)
* คลาส [IHtmlGenerator](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)