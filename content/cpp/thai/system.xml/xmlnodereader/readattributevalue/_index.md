---
title: ReadAttributeValue()
second_title: Aspose.Slides สำหรับเอกสารอ้างอิง API ของ C++
description: แยกวิเคราะห์ค่าแอตทริบิวต์เป็นหนึ่งหรือหลายโหนด Text, EntityReference หรือ EndEntity.
type: docs
weight: 430
url: /th/system.xml/xmlnodereader/readattributevalue/
---
## XmlNodeReader::ReadAttributeValue() เมธอด

แยกวิเคราะห์ค่าแอตทริบิวต์เป็นหนึ่งหรือหลายโหนด **[Text](../../../system.text/)**, **EntityReference** หรือ **EndEntity**.

```cpp
bool System::Xml::XmlNodeReader::ReadAttributeValue() override
```

### ค่าที่ส่งคืน

**true** หากมีโหนดที่จะส่งคืน. **false** หากตัวอ่านไม่ได้อยู่บนโหนดแอตทริบิวต์เมื่อทำการเรียกครั้งแรกหรือหากค่าแอตทริบิวต์ทั้งหมดถูกอ่านแล้ว. แอตทริบิวต์ที่ว่างเปล่า เช่น **misc=\"\"** ส่งคืน **true** พร้อมโหนดเดียวที่มีค่าเป็น [String::Empty](../../../system/string/empty/).

## ดูเพิ่มเติม

* คลาส [XmlNodeReader](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)