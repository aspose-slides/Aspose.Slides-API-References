---
title: AppendText()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างอ็อบเจกต์ StreamWriter ที่เพิ่มข้อความลงในไฟล์ที่ระบุโดยใช้การเข้ารหัส UTF-8 หากไฟล์ที่ระบุไม่มีอยู่ จะทำการสร้างไฟล์ใหม่
type: docs
weight: 27
url: /th/system.io/file/appendtext/
---
## File::AppendText(const String\&) วิธี

สร้างอ็อบเจกต์ [StreamWriter](../../streamwriter/) ที่เพิ่มข้อความลงในไฟล์ที่ระบุโดยใช้การเข้ารหัส UTF-8 หากไฟล์ที่ระบุไม่มีอยู่ จะทำการสร้างไฟล์ใหม่

```cpp
static StreamWriterPtr System::IO::File::AppendText(const String &path)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | เส้นทางของไฟล์ที่จะเปิดหรือสร้าง |

### ค่าที่ส่งกลับ

พอยน์เตอร์แบบแชร์ไปยังอ็อบเจกต์ [StreamWriter](../../streamwriter/) ที่สร้างขึ้นและเชื่อมโยงกับไฟล์ที่ระบุ

## ดูเพิ่มเติม

* การกำหนดชนิด [StreamWriterPtr](../../../system/streamwriterptr/)
* คลาส [String](../../../system/string/)
* คลาส [File](../)
* เนมสเปซ [System::IO](../../)
* ไลบรารี [Aspose.Slides](../../../)