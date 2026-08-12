---
title: ReadState
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: ระบุสถานะของรีดเดอร์.
type: docs
weight: 703
url: /th/system.xml/readstate/
---
## ReadState enum

กำหนดสถานะของรีดเดอร์

```cpp
enum class ReadState
```

### ค่า

| Name | Value | Description |
| --- | --- | --- |
| Initial | 0 | เมธอด [XmlReader::Read](../xmlreader/read/) ยังไม่ได้ถูกเรียกใช้. |
| Interactive | 1 | เมธอด [XmlReader::Read](../xmlreader/read/) ได้ถูกเรียกใช้แล้ว. เมธอดเพิ่มเติมอาจถูกเรียกบนรีดเดอร์. |
| Error | 2 | เกิดข้อผิดพลาดที่ทำให้การดำเนินการอ่านไม่สามารถดำเนินต่อได้. |
| EndOfFile | 3 | ถึงจุดสิ้นสุดของไฟล์แล้วสำเร็จ. |
| Closed | 4 | เมธอด [XmlReader::Close](../xmlreader/close/) ได้ถูกเรียกใช้แล้ว. |

## ดูเพิ่มเติม

* เนมสเปซ [System::Xml](../)
* ไลบรารี [Aspose.Slides](../../)