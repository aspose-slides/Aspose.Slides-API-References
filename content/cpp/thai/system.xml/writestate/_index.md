---
title: WriteState
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: ระบุสถานะของ XmlWriter.
type: docs
weight: 755
url: /th/system.xml/writestate/
---
## WriteState enum

ระบุสถานะของ [XmlWriter](../xmlwriter/).

```cpp
enum class WriteState
```

### ค่าต่างๆ

| ชื่อ | ค่า | คำอธิบาย |
| --- | --- | --- |
| Start | 0 | บ่งบอกว่าเมธอด XmlWriter::Write ยังไม่ได้ถูกเรียกใช้. |
| Prolog | 1 | บ่งบอกว่ากำลังเขียน prolog. |
| Element | 2 | บ่งบอกว่ากำลังเขียนแท็กเริ่มต้นของ element. |
| Attribute | 3 | บ่งบอกว่ากำลังเขียนค่าของ attribute. |
| Content | 4 | บ่งบอกว่ากำลังเขียนเนื้อหาของ element. |
| Closed | 5 | บ่งบอกว่าเมธอด [XmlWriter::Close](../xmlwriter/close/) ถูกเรียกใช้. |
| Error | 6 | ข้อยกเว้นได้ถูก throw แล้ว ทำให้ [XmlWriter](../xmlwriter/) อยู่ในสถานะที่ไม่ถูกต้อง. คุณสามารถเรียกเมธอด [XmlWriter::Close](../xmlwriter/close/) เพื่อใส่ [XmlWriter](../xmlwriter/) ให้อยู่ในสถานะ [WriteState::Closed](./). การเรียกเมธอด [XmlWriter](../xmlwriter/) ใด ๆ เพิ่มเติมจะทำให้เกิด InvalidOperationException. |

## ดูเพิ่มเติม

* เนมสเปซ [System::Xml](../)
* ไลบรารี [Aspose.Slides](../../)