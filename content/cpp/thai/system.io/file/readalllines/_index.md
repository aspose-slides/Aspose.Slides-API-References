---
title: ReadAllLines()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: อ่านเนื้อหาของไฟล์ข้อความที่ระบุแบบบรรทัดต่อบรรทัดเป็นอาเรย์ของสตริงโดยใช้การเข้ารหัสอักขระที่กำหนด
type: docs
weight: 300
url: /th/system.io/file/readalllines/
---
## File::ReadAllLines(const String\&, const EncodingPtr\&) เมธอด

อ่านเนื้อหาของไฟล์ข้อความที่ระบุแบบบรรทัดต่อบรรทัดเป็นอาเรย์ของสตริงโดยใช้การเข้ารหัสอักขระที่ระบุ

```cpp
static ArrayPtr<String> System::IO::File::ReadAllLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | เส้นทางของไฟล์ที่ต้องการอ่าน |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | การเข้ารหัสอักขระที่จะใช้ |

## ค่าที่คืนกลับ

อาเรย์ของสตริงที่แต่ละองค์ประกอบเป็นตัวแทนของบรรทัดเดียวจากไฟล์ที่ระบุ

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)