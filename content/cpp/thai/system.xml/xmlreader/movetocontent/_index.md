---
title: MoveToContent()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "ตรวจสอบว่าโหนดปัจจุบันเป็นโหนดเนื้อหา (ข้อความที่ไม่เป็นช่องว่าง, CDATA, Element, EndElement, EntityReference หรือ EndEntity) หรือไม่ หากโหนดไม่ใช่โหนดเนื้อหา ตัวอ่านจะข้ามไปยังโหนดเนื้อหาถัดไปหรือถึงจุดสิ้นสุดของไฟล์ มันจะข้ามโหนดประเภทต่อไปนี้: ProcessingInstruction, DocumentType, Comment, Whitespace หรือ SignificantWhitespace."
type: docs
weight: 833
url: /th/system.xml/xmlreader/movetocontent/
---
## XmlReader::MoveToContent() เมธอด

ตรวจสอบว่าโหนดปัจจุบันเป็นโหนดเนื้อหา (ข้อความที่ไม่ใช่ช่องว่าง, **CDATA**, **Element**, **EndElement**, **EntityReference**, หรือ **EndEntity**) หรือไม่ หากโหนดไม่ใช่โหนดเนื้อหา ตัวอ่านจะข้ามไปยังโหนดเนื้อถัดไปหรือจนถึงจุดสิ้นสุดของไฟล์ ตัวอ่านจะข้ามโหนดประเภทต่อไปนี้: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace**, หรือ **SignificantWhitespace**.

```cpp
virtual XmlNodeType System::Xml::XmlReader::MoveToContent()
```

### ค่าที่ส่งคืน

ค่า [XmlReader::get_NodeType](../get_nodetype/) ของโหนดปัจจุบันที่พบโดยเมธอด หรือ [XmlNodeType::None](../../xmlnodetype/) หากตัวอ่านถึงจุดสิ้นสุดของสตรีมอินพุต.

## ดูเพิ่มเติม

* Enum [XmlNodeType](../../xmlnodetype/)
* คลาส [XmlReader](../)
* เนมสเปซ [System::Xml](../../)
* Library [Aspose.Slides](../../../)