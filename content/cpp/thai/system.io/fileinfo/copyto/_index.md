---
title: CopyTo()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: คัดลอกไฟล์ที่แสดงโดยอ็อบเจกต์ปัจจุบันไปยังตำแหน่งที่ระบุ หากไฟล์ปลายทางมีอยู่แล้ว การคัดลอกจะล้มเหลว
type: docs
weight: 105
url: /th/system.io/fileinfo/copyto/
---
## FileInfo::CopyTo(const String\&) เมธอด

คัดลอกไฟล์ที่อ้างอิงโดยอ็อบเจกต์ปัจจุบันไปยังตำแหน่งที่กำหนด หากไฟล์ปลายทางมีอยู่แล้ว การคัดลอกจะล้มเหลว

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| destFileName | const [String](../../../system/string/)\& | ชื่อไฟล์ปลายทาง |

### ค่าที่คืนกลับ

วัตถุ [FileInfo](../) ที่แสดงถึงการคัดลอก

## FileInfo::CopyTo(const String\&, bool) เมธอด

คัดลอกไฟล์ที่อ้างอิงโดยอ็อบเจกต์ปัจจุบันไปยังตำแหน่งที่กำหนด พารามิเตอร์ระบุว่าควรเขียนทับไฟล์ปลายทางที่มีอยู่หรือไม่

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName, bool overwrite)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| destFileName | const [String](../../../system/string/)\& | ชื่อไฟล์ปลายทาง |
| overwrite | **bool** | true หากต้องการเขียนทับไฟล์ปลายทางที่มีอยู่, false หากการคัดลอกควรล้มเหลือหากไฟล์ปลายทางมีอยู่แล้ว |

### ค่าที่คืนกลับ

วัตถุ [FileInfo](../) ที่แสดงถึงการคัดลอก

## ดูเพิ่มเติม

* การกำหนดชนิด [FileInfoPtr](../../../system/fileinfoptr/)
* คลาส [String](../../../system/string/)
* คลาส [FileInfo](../)
* เนมสเปซ [System::IO](../../)
* ไลบรารี [Aspose.Slides](../../../)