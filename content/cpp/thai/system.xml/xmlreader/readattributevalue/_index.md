---
title: ReadAttributeValue()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: เมื่อถูก override ในคลาสที่สืบทอด จะวิเคราะห์ค่าแอตทริบิวต์เป็นหนึ่งหรือหลายโหนด Text, EntityReference หรือ EndEntity nodes.
type: docs
weight: 677
url: /th/system.xml/xmlreader/readattributevalue/
---
## XmlReader::ReadAttributeValue() เมธอด

เมื่อถูก override ในคลาสที่สืบทอด, จะวิเคราะห์ค่าแอตทริบิวต์เป็นหนึ่งหรือหลายโหนด **[Text](../../../system.text/)**, **EntityReference**, หรือ **EndEntity** โหนด.

```cpp
virtual bool System::Xml::XmlReader::ReadAttributeValue()=0
```

### ค่าที่คืน

**true** ถ้ามีโหนดที่จะคืนค่า. **false** ถ้า reader ไม่ได้อยู่บนโหนดแอตทริบิวต์เมื่อทำการเรียกครั้งแรกหรือถ้าค่าแอตทริบิวต์ทั้งหมดถูกอ่านแล้ว. แอตทริบิวต์ว่าง, เช่น **misc=""**, จะคืนค่า **true** พร้อมโหนดเดียวที่มีค่าของ [String::Empty](../../../system/string/empty/).

## ดูเพิ่มเติม

* คลาส [XmlReader](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)