---
title: CreateFileStreamWrapper()
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: สร้าง FileStream ด้วยเส้นทางและโหมดการสร้างที่ระบุ.
type: docs
weight: 14
url: /th/aspose.slides/istreamwrapperfactory/createfilestreamwrapper/
---
## IStreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode) เมธอด

สร้าง FileStream ด้วยเส้นทางและโหมดการสร้างที่ระบุ.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fileName | [System::String](../../../system/string/) | ชื่อไฟล์ [System::String](../../../system/string/) |
| fileMode | [System::IO::FileMode](../../../system.io/filemode/) | โหมดไฟล์ [System::IO::FileMode](../../../system.io/filemode/) |

### ค่าที่ส่งคืน

ตัวห่อ Stream สำหรับ COM interface [IStreamWrapper](../../istreamwrapper/)

## IStreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode, System::IO::FileAccess) เมธอด

สร้าง FileStream ด้วยเส้นทาง, โหมดการสร้าง และสิทธิ์การอ่าน/เขียนที่ระบุ.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode, System::IO::FileAccess fileAccess)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fileName | [System::String](../../../system/string/) | ชื่อไฟล์ [System::String](../../../system/string/) |
| fileMode | [System::IO::FileMode](../../../system.io/filemode/) | โหมดไฟล์ [System::IO::FileMode](../../../system.io/filemode/) |
| fileAccess | [System::IO::FileAccess](../../../system.io/fileaccess/) | การเข้าถึงไฟล์ [System::IO::FileAccess](../../../system.io/fileaccess/) |

### ค่าที่ส่งคืน

ตัวห่อ Stream สำหรับ COM interface [IStreamWrapper](../../istreamwrapper/)

## ดูเพิ่มเติม

* Enum [FileMode](../../../system.io/filemode/)
* Enum [FileAccess](../../../system.io/fileaccess/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IStreamWrapper](../../istreamwrapper/)
* คลาส [String](../../../system/string/)
* คลาส [IStreamWrapperFactory](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)