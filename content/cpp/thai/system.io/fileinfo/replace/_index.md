---
title: Replace()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แทนที่เนื้อหาของไฟล์ปลายทางที่ระบุด้วยไฟล์ที่อ็อบเจกต์ FileInfo ปัจจุบันเป็นตัวแทน และสร้างไฟล์สำรองของไฟล์ที่ถูกแทนที่
type: docs
weight: 131
url: /th/system.io/fileinfo/replace/
---
## FileInfo::Replace(const String\&, const String\&) เมธอด

แทนที่เนื้อหาของไฟล์ปลายทางที่ระบุด้วยไฟล์ที่อ็อบเจกต์ [FileInfo](../) ปัจจุบันเป็นตัวแทน และสร้างไฟล์สำรองของไฟล์ที่ถูกแทนที่

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| destinationFileName | const [String](../../../system/string/)\& | ชื่อไฟล์ที่ต้องการแทนที่ |
| destinationBackupFileName | const [String](../../../system/string/)\& | ชื่อไฟล์สำรอง |

### ค่ารีเทิร์น

ออบเจกต์ FileInfor ที่แสดงถึงไฟล์ที่ชี้โดย **destinationFileName**

## FileInfo::Replace(const String\&, const String\&, bool) เมธอด

แทนที่เนื้อหาของไฟล์ปลายทางที่ระบุด้วยไฟล์ที่อ็อบเจกต์ [FileInfo](../) ปัจจุบันเป็นตัวแทน และสร้างไฟล์สำรองของไฟล์ที่ถูกแทนที่

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| destinationFileName | const [String](../../../system/string/)\& | ชื่อไฟล์ที่ต้องการแทนที่ |
| destinationBackupFileName | const [String](../../../system/string/)\& | ชื่อไฟล์สำรอง |
| ignoreMetadataErrors | **bool** | ระบุว่าควรละเว้นข้อผิดพลาดการรวมจากไฟล์ที่ถูกแทนที่ไปยังไฟล์ที่ใช้แทนที่หรือไม่ (true) หรือ (false) |

### ค่ารีเทิร์น

ออบเจกต์ FileInfor ที่แสดงถึงไฟล์ที่ชี้โดย **destinationFileName**

## ดูเพิ่มเติม

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* คลาส [String](../../../system/string/)
* คลาส [FileInfo](../)
* เนมสเปซ [System::IO](../../)
* ไลบรารี [Aspose.Slides](../../../)