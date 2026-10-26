---
title: Add()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เพิ่มส่วน XML แบบกำหนดเองใหม่.
type: docs
weight: 53
url: /th/aspose.slides/customxmlpartcollection/add/
---
## CustomXmlPartCollection::Add(System::String) เมธอด


เพิ่มส่วน XML แบบกำหนดเองใหม่.

```cpp
System::SharedPtr<ICustomXmlPart> Aspose::Slides::CustomXmlPartCollection::Add(System::String xmlString) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xmlString | [System::String](../../../system/string/) | สตริง XML ของส่วนใหม่ที่ต้องการเพิ่ม. |

### ค่าที่ส่งกลับ

ส่วน XML แบบกำหนดเองที่สร้างขึ้น.

## CustomXmlPartCollection::Add(System::ArrayPtr\<uint8_t\>) เมธอด


เพิ่มส่วน XML แบบกำหนดเองใหม่.

```cpp
System::SharedPtr<ICustomXmlPart> Aspose::Slides::CustomXmlPartCollection::Add(System::ArrayPtr<uint8_t> xmlData) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xmlData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | ข้อมูล XML ของส่วนใหม่ที่ต้องการเพิ่ม. |

### ค่าที่ส่งกลับ

ส่วน XML แบบกำหนดเองที่สร้างขึ้น.

## CustomXmlPartCollection::Add(System::SharedPtr\<System::IO::Stream\>) เมธอด


เพิ่มส่วน XML แบบกำหนดเองใหม่.

```cpp
System::SharedPtr<ICustomXmlPart> Aspose::Slides::CustomXmlPartCollection::Add(System::SharedPtr<System::IO::Stream> inputStream) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| inputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | inputStream ที่มีข้อมูล XML ของส่วนใหม่ที่ต้องการเพิ่ม. |

### ค่าที่ส่งกลับ

ส่วน XML แบบกำหนดเองที่สร้างขึ้น.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [ICustomXmlPart](../../icustomxmlpart/)
* คลาส [String](../../../system/string/)
* คลาส [CustomXmlPartCollection](../)
* คลาส [Stream](../../../system.io/stream/)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)