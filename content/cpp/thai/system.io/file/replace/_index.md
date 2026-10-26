---
title: Replace()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แทนที่เนื้อหาของไฟล์หนึ่งด้วยไฟล์อื่นและสร้างสำเนาสำรองของไฟล์ที่ถูกแทนที่
type: docs
weight: 339
url: /th/system.io/file/replace/
---
## File::Replace(const String\&, const String\&, const String\&, bool) เมธอด

แทนที่เนื้อหาของไฟล์หนึ่งด้วยไฟล์อื่นและสร้างสำเนาสำรองของไฟล์ที่ถูกแทนที่.

```cpp
static void System::IO::File::Replace(const String &sourceFileName, const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors=1)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sourceFileName | const [String](../../../system/string/)\& | ชื่อของไฟล์ที่จะใช้แทนที่ |
| destinationFileName | const [String](../../../system/string/)\& | ชื่อของไฟล์ที่จะถูกแทนที่ |
| destinationBackupFileName | const [String](../../../system/string/)\& | ชื่อของไฟล์สำเนาสำรอง |
| ignoreMetadataErrors | **bool** | ระบุว่าควรละเว้นข้อผิดพลาดการผสานจากไฟล์ที่ถูกแทนที่ไปยังไฟล์แทนที่หรือไม่ (true) หรือ (false) |

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [File](../)
* เนมสเปซ [System::IO](../../)
* ไลบรารี [Aspose.Slides](../../../)