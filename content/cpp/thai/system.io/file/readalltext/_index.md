---
title: ReadAllText()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: อ่านเนื้อหาของไฟล์ข้อความที่ระบุไปยังอ็อบเจกต์ String เดียวโดยใช้การเข้ารหัสอักขระที่ระบุ.
type: docs
weight: 313
url: /th/system.io/file/readalltext/
---
## File::ReadAllText(const String\&, const EncodingPtr\&) เมธอด

อ่านเนื้อหาของไฟล์ข้อความที่ระบุไปยังอ็อบเจกต์ [String](../../../system/string/) เดียวโดยใช้การเข้ารหัสอักขระที่ระบุ

```cpp
static String System::IO::File::ReadAllText(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | เส้นทางของไฟล์ที่ต้องการอ่าน |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | การเข้ารหัสอักขระที่ใช้ |

### ค่าที่ส่งคืน

สตริงที่มีเนื้อหาของไฟล์ที่ระบุ

## ดูเพิ่มเติม

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)