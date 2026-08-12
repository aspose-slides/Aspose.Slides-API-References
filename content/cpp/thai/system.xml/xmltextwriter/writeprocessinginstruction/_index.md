---
title: WriteProcessingInstruction()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "เขียนคำสั่งประมวลผลโดยมีช่องว่างระหว่างชื่อและข้อความดังนี้: <?name text?>."
type: docs
weight: 326
url: /th/system.xml/xmltextwriter/writeprocessinginstruction/
---
## XmlTextWriter::WriteProcessingInstruction(String, String) เมธอด

เขียนคำสั่งประมวลผลโดยมีช่องว่างระหว่างชื่อและข้อความดังนี้: **<?name text?>**.

```cpp
void System::Xml::XmlTextWriter::WriteProcessingInstruction(String name, String text) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อของคำสั่งประมวลผล |
| text | [String](../../../system/string/) | [Text](../../../system.text/) เพื่อรวมไว้ในคำสั่งประมวลผล |

## หมายเหตุ

เมธอดนี้ถูกใช้เพื่อสร้างการประกาศ XML หลังจากที่ [XmlTextWriter::WriteStartDocument](../writestartdocument/) ได้ถูกเรียกแล้ว

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlTextWriter](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)