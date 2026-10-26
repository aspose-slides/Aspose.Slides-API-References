---
title: OpenText()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: เปิดไฟล์ที่มีอยู่แล้วตามที่ระบุเพื่ออ่านข้อความโดยใช้การเข้ารหัส UTF-8 โดยไม่มีการแชร์
type: docs
weight: 261
url: /th/system.io/file/opentext/
---
## File::OpenText(const String\&, const EncodingPtr\&) เมธอด


เปิดไฟล์ที่มีอยู่แล้วตามที่ระบุเพื่ออ่านข้อความโดยใช้การเข้ารหัส UTF-8 โดยไม่มีการแชร์

```cpp
static StreamReaderPtr System::IO::File::OpenText(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | เส้นทางของไฟล์ที่ต้องการเปิด |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | การเข้ารหัสอักขระที่ใช้ |

### ค่าที่ส่งกลับ

ตัวชี้ shared pointer ไปยังอ็อบเจกต์ [StreamWriter](../../streamwriter/) ที่เชื่อมโยงกับไฟล์ที่เปิด

## ดูเพิ่มเติม

* Typedef [StreamReaderPtr](../../../system/streamreaderptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)