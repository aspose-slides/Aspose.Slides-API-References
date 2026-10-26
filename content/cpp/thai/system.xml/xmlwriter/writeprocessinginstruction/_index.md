---
title: WriteProcessingInstruction()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "เมื่อถูกทำซ้ำในคลาสที่สืบทอด, จะเขียนคำสั่งประมวลผลโดยมีช่องว่างระหว่างชื่อและข้อความดังนี้: <?name text?>."
type: docs
weight: 196
url: /th/system.xml/xmlwriter/writeprocessinginstruction/
---
## XmlWriter::WriteProcessingInstruction(String, String) เมธอด


When overridden in a derived class, writes out a processing instruction with a space between the name and text as follows: **<?name text?>**.

```cpp
virtual void System::Xml::XmlWriter::WriteProcessingInstruction(String name, String text)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อของคำสั่งประมวลผล. |
| text | [String](../../../system/string/) | ข้อความที่ต้องรวมไว้ในคำสั่งประมวลผล. |
## หมายเหตุ



เมธอดนี้กำลังถูกใช้เพื่อสร้างการประกาศ XML หลังจากที่ได้เรียก [XmlWriter::WriteStartDocument](../writestartdocument/) ไปแล้ว. 
## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlWriter](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)