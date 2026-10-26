---
title: ReadPresentation()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: อ่านงานนำเสนอที่มีอยู่จากอาเรย์
type: docs
weight: 27
url: /th/aspose.slides/ipresentationfactory/readpresentation/
---
## IPresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>) วิธีการ

อ่านงานนำเสนอที่มีอยู่จากอาเรย์

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | อาเรย์สำหรับอ่าน |

### ค่าที่คืนกลับ

อ่านงานนำเสนอ

## IPresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<ILoadOptions\>) วิธีการ

อ่านงานนำเสนอที่มีอยู่จากอาเรย์พร้อมตัวเลือกการโหลดเพิ่มเติม

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data, System::SharedPtr<ILoadOptions> options)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | อาเรย์สำหรับอ่าน |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | ตัวเลือกการโหลด |

### ค่าที่คืนกลับ

อ่านงานนำเสนอ

## IPresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>) วิธีการ

อ่านงานนำเสนอที่มีอยู่จากสตรีม

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | สตรีมอินพุตสำหรับอ่าน |

### ค่าที่คืนกลับ

อ่านงานนำเสนอ

## IPresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<ILoadOptions\>) วิธีการ

อ่านงานนำเสนอที่มีอยู่จากสตรีมพร้อมตัวเลือกการโหลดเพิ่มเติม

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<ILoadOptions> options)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | สตรีมอินพุตสำหรับอ่าน |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | ตัวเลือกการโหลด |

### ค่าที่คืนกลับ

อ่านงานนำเสนอ

## IPresentationFactory::ReadPresentation(System::String) วิธีการ

อ่านงานนำเสนอที่มีอยู่จากไฟล์

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::String file)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | ชื่อไฟล์ |

### ค่าที่คืนกลับ

อ่านงานนำเสนอ

## IPresentationFactory::ReadPresentation(System::String, System::SharedPtr\<ILoadOptions\>) วิธีการ

อ่านงานนำเสนอที่มีอยู่จากไฟล์พร้อมตัวเลือกการโหลดเพิ่มเติม

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::String file, System::SharedPtr<ILoadOptions> options)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | ชื่อไฟล์ |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | ตัวเลือกการโหลด |

### ค่าที่คืนกลับ

อ่านงานนำเสนอ

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [IPresentation](../../ipresentation/)
* คลาส [IPresentationFactory](../)
* คลาส [ILoadOptions](../../iloadoptions/)
* คลาส [Stream](../../../system.io/stream/)
* คลาส [String](../../../system/string/)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)