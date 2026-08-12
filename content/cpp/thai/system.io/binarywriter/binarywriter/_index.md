---
title: BinaryWriter()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างอินสแตนซ์ของคลาส BinaryWriter ที่เขียนข้อมูลไปยังสตรีมที่ระบุโดยใช้การเข้ารหัสที่ระบุ
type: docs
weight: 1
url: /th/system.io/binarywriter/binarywriter/
---
## BinaryWriter::BinaryWriter(const StreamPtr\&, const EncodingPtr\&, bool) constructor

สร้างอินสแตนซ์ของคลาส [BinaryWriter](../) ที่เขียนข้อมูลไปยังสตรีมที่ระบุโดยใช้การเข้ารหัสที่ระบุ

```cpp
System::IO::BinaryWriter::BinaryWriter(const StreamPtr &stream, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked(), bool leaveopen=false)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | สตรีมเอาต์พุต |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | การเข้ารหัสที่ใช้ |
| leaveopen | **bool** | ระบุว่า สตรีม **stream** ควรเปิดไว้ (true) หลังจากวัตถุปัจจุบันถูกทำลายหรือไม่ (false) |

## ดูเพิ่มเติม

* Typedef [StreamPtr](../../../system/streamptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [BinaryWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)