---
title: CreateMemoryStreamWrapper()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้าง wrapper MemoryStream.
type: docs
weight: 1
url: /th/aspose.slides/istreamwrapperfactory/creatememorystreamwrapper/
---
## IStreamWrapperFactory::CreateMemoryStreamWrapper() เมธอด

สร้าง wrapper MemoryStream.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateMemoryStreamWrapper()=0
```

### ค่าที่ส่งกลับ

wrapper ของ COM interface [IStreamWrapper](../../istreamwrapper/)

## IStreamWrapperFactory::CreateMemoryStreamWrapper(System::ArrayPtr\<uint8_t\>) เมธอด

สร้าง wrapper MemoryStream ตามอาร์เรย์ไบต์ที่ระบุ

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateMemoryStreamWrapper(System::ArrayPtr<uint8_t> buffer)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | อาร์เรย์ไบต์ **uint8_t**[] |

### ค่าที่ส่งกลับ

wrapper ของ COM interface [IStreamWrapper](../../istreamwrapper/)

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [IStreamWrapper](../../istreamwrapper/)
* คลาส [IStreamWrapperFactory](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)