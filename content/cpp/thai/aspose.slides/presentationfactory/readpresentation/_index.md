---
title: ReadPresentation()
second_title: Aspose.Slides สำหรับเอกสารอ้างอิง API C++
description: อ่านงานนำเสนอที่มีอยู่จากอาเรย์
type: docs
weight: 40
url: /th/aspose.slides/presentationfactory/readpresentation/
---
## PresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>) เมธอด

อ่านงานนำเสนอที่มีอยู่จากอาเรย์

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | อาเรย์ที่ต้องการอ่าน |

### ค่าที่คืนกลับ

งานนำเสนอที่อ่าน

## PresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<ILoadOptions\>) เมธอด

อ่านงานนำเสนอที่มีอยู่จากอาเรย์พร้อมตัวเลือกการโหลดเพิ่มเติม

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data, System::SharedPtr<ILoadOptions> options) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | อาเรย์ที่ต้องการอ่าน |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | ตัวเลือกการโหลด |

### ค่าที่คืนกลับ

งานนำเสนอที่อ่าน

## PresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>) เมธอด

อ่านงานนำเสนอที่มีอยู่จากสตรีม

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | สตรีมอินพุตที่ต้องการอ่าน |

### ค่าที่คืนกลับ

งานนำเสนอที่อ่าน

## PresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<ILoadOptions\>) เมธอด

อ่านงานนำเสนอที่มีอยู่จากสตรีมพร้อมตัวเลือกการโหลดเพิ่มเติม

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<ILoadOptions> options) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | สตรีมอินพุตที่ต้องการอ่าน |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | ตัวเลือกการโหลด |

### ค่าที่คืนกลับ

งานนำเสนอที่อ่าน

## PresentationFactory::ReadPresentation(System::String) เมธอด

อ่านงานนำเสนอที่มีอยู่จากไฟล์

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::String file) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | ชื่อไฟล์ |

### ค่าที่คืนกลับ

งานนำเสนอที่อ่าน

## PresentationFactory::ReadPresentation(System::String, System::SharedPtr\<ILoadOptions\>) เมธอด

อ่านงานนำเสนอที่มีอยู่จากไฟล์พร้อมตัวเลือกการโหลดเพิ่มเติม

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::String file, System::SharedPtr<ILoadOptions> options) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | ชื่อไฟล์ |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | ตัวเลือกการโหลด |

### ค่าที่คืนกลับ

งานนำเสนอที่อ่าน

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [IPresentation](../../ipresentation/)
* คลาส [PresentationFactory](../)
* คลาส [ILoadOptions](../../iloadoptions/)
* คลาส [Stream](../../../system.io/stream/)
* คลาส [String](../../../system/string/)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)