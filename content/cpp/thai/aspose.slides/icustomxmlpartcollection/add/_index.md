---
title: Add()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: เพิ่มส่วน XML ที่กำหนดเองใหม่.
type: docs
weight: 14
url: /th/aspose.slides/icustomxmlpartcollection/add/
---
## ICustomXmlPartCollection::Add(System::ArrayPtr\<uint8_t\>) method

เพิ่มส่วน XML ที่กำหนดเองใหม่.

```cpp
virtual System::SharedPtr<ICustomXmlPart> Aspose::Slides::ICustomXmlPartCollection::Add(System::ArrayPtr<uint8_t> xmlData)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| xmlData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | ข้อมูล XML ของส่วนใหม่ที่จะถูกเพิ่ม. |

### ค่าที่ส่งคืน

สร้างส่วน XML ที่กำหนดเองขึ้น.

## ICustomXmlPartCollection::Add(System::String) method

เพิ่มส่วน XML ที่กำหนดเองใหม่.

```cpp
virtual System::SharedPtr<ICustomXmlPart> Aspose::Slides::ICustomXmlPartCollection::Add(System::String xmlString)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| xmlString | [System::String](../../../system/string/) | สตริง XML ของส่วนใหม่ที่จะถูกเพิ่ม. |

### ค่าที่ส่งคืน

สร้างส่วน XML ที่กำหนดเองขึ้น.

## ICustomXmlPartCollection::Add(System::SharedPtr\<System::IO::Stream\>) method

เพิ่มส่วน XML ที่กำหนดเองใหม่.

```cpp
virtual System::SharedPtr<ICustomXmlPart> Aspose::Slides::ICustomXmlPartCollection::Add(System::SharedPtr<System::IO::Stream> inputStream)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| inputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | inputStream ที่มีข้อมูล XML ของส่วนใหม่ที่จะถูกเพิ่ม. |

### ค่าที่ส่งคืน

สร้างส่วน XML ที่กำหนดเองขึ้น.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICustomXmlPart](../../icustomxmlpart/)
* Class [ICustomXmlPartCollection](../)
* Class [String](../../../system/string/)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)