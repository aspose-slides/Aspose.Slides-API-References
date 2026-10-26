---
title: GetPresentationInfo()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ดึงข้อมูลเกี่ยวกับงานนำเสนอจากไฟล์ที่ระบุ.
type: docs
weight: 14
url: /th/aspose.slides/ipresentationfactory/getpresentationinfo/
---
## IPresentationFactory::GetPresentationInfo(System::String) เมธอด

ดึงข้อมูลเกี่ยวกับงานนำเสนอจากไฟล์ที่ระบุ.

```cpp
virtual System::SharedPtr<IPresentationInfo> Aspose::Slides::IPresentationFactory::GetPresentationInfo(System::String file)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | [Presentation](../../presentation/) ไฟล์. |

### ค่าที่คืน

[Presentation](../../presentation/) ข้อมูล

## IPresentationFactory::GetPresentationInfo(System::SharedPtr\<System::IO::Stream\>) เมธอด

ดึงข้อมูลเกี่ยวกับงานนำเสนอจากสตรีมที่ระบุ.

```cpp
virtual System::SharedPtr<IPresentationInfo> Aspose::Slides::IPresentationFactory::GetPresentationInfo(System::SharedPtr<System::IO::Stream> stream)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | [Presentation](../../presentation/) สตรีม. |

### ค่าที่คืน

[Presentation](../../presentation/) ข้อมูล.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPresentationInfo](../../ipresentationinfo/)
* Class [String](../../../system/string/)
* Class [IPresentationFactory](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)