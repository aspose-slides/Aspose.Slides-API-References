---
title: WriteAllText()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างไฟล์ข้อความใหม่หรือเขียนทับไฟล์ที่มีอยู่แล้วและเขียนเนื้อหาของสตริงที่ระบุลงในไฟล์โดยใช้การเข้ารหัสที่ระบุ
type: docs
weight: 469
url: /th/system.io/file/writealltext/
---
## File::WriteAllText(const String&, const String&, const EncodingPtr&) เมธอด

สร้างไฟล์ข้อความใหม่หรือเขียนทับไฟล์ที่มีอยู่แล้วและเขียนเนื้อหาของสตริงที่ระบุลงในไฟล์โดยใช้การเข้ารหัสที่ระบุ

```cpp
static void System::IO::File::WriteAllText(const String &path, const String &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | ไฟล์ที่จะสร้างหรือเขียนทับ |
| contents | const [String](../../../system/string/)\& | อาร์เรย์ของสตริง |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | การเข้ารหัสอักขระที่ใช้ |

## ดูเพิ่มเติม

* Typedef [EncodingPtr](../../../system/encodingptr/)
* คลาส [String](../../../system/string/)
* คลาส [File](../)
* เนมสเปซ [System::IO](../../)
* ไลบรารี [Aspose.Slides](../../../)