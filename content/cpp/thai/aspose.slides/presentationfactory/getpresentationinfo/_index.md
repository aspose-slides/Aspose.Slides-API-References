---
title: GetPresentationInfo()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างอ็อบเจ็กต์ PresentationInfo ใหม่จากไฟล์และผูกการนำเสนอเข้ากับอ็อบเจ็กต์นั้น.
type: docs
weight: 27
url: /th/aspose.slides/presentationfactory/getpresentationinfo/
---
## PresentationFactory::GetPresentationInfo(System::String) เมธอด

สร้างอ็อบเจ็กต์ [PresentationInfo](../../presentationinfo/) ใหม่จากไฟล์และทำการผูกการนำเสนอเข้ากับอ็อบเจ็กต์นั้น.

```cpp
System::SharedPtr<IPresentationInfo> Aspose::Slides::PresentationFactory::GetPresentationInfo(System::String file) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | [Presentation](../../presentation/) ไฟล์. |

### ค่าที่ส่งคืน

[Presentation](../../presentation/) ข้อมูลที่ผูกกับการนำเสนอ.

## PresentationFactory::GetPresentationInfo(System::SharedPtr\<System::IO::Stream\>) เมธอด

สร้างอ็อบเจ็กต์ [PresentationInfo](../../presentationinfo/) ใหม่จากสตรีมและทำการผูกการนำเสนอเข้ากับอ็อบเจ็กต์นั้น. รับข้อมูลเกี่ยวกับการนำเสนอในสตรีมที่ระบุ.

```cpp
System::SharedPtr<IPresentationInfo> Aspose::Slides::PresentationFactory::GetPresentationInfo(System::SharedPtr<System::IO::Stream> stream) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | [Presentation](../../presentation/) สตรีม. |

### ค่าที่ส่งคืน

[Presentation](../../presentation/) ข้อมูลที่ผูกกับการนำเสนอ.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IPresentationInfo](../../ipresentationinfo/)
* คลาส [String](../../../system/string/)
* คลาส [PresentationFactory](../)
* คลาส [Stream](../../../system.io/stream/)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)