---
title: ReadAttributeValue()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แยกค่าคุณสมบัติออกเป็นหนึ่งหรือหลายโหนด Text, EntityReference, หรือ EndEntity
type: docs
weight: 560
url: /th/system.xml/xmltextreader/readattributevalue/
---
## XmlTextReader::ReadAttributeValue() เมธอด

แยกค่าคุณสมบัติออกเป็นหนึ่งหรือหลาย **[Text](../../../system.text/)**, **EntityReference**, หรือ **EndEntity** โหนด.

```cpp
bool System::Xml::XmlTextReader::ReadAttributeValue() override
```

### ค่าที่ส่งกลับ

**true** หากมีโหนดให้ส่งคืน. **false** หากตัวอ่านไม่ได้อยู่บนโหนดแอตทริบิวต์เมื่อทำการเรียกครั้งแรกหรือหากค่าคุณสมบัติเ�ทั้งหมดถูกอ่านแล้ว. แอตทริบิวต์ที่ว่างเปล่า เช่น **misc=\"\"**, จะคืนค่า **true** พร้อมโหนดเดียวที่มีค่าของ [String::Empty](../../../system/string/empty/).

## ดูเพิ่มเติม

* คลาส [XmlTextReader](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)