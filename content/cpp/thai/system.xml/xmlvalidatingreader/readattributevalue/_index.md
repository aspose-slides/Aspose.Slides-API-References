---
title: ReadAttributeValue()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แยกวิเคราะห์ค่าคุณลักษณะเป็นโหนด Text, EntityReference หรือ EndEntity หนึ่งหรือหลายโหนด.
type: docs
weight: 508
url: /th/system.xml/xmlvalidatingreader/readattributevalue/
---
## XmlValidatingReader::ReadAttributeValue() เมธอด

แยกวิเคราะห์ค่าคุณลักษณะเป็นโหนด **[Text](../../../system.text/)**, **EntityReference** หรือ **EndEntity** หนึ่งหรือหลายโหนด.

```cpp
bool System::Xml::XmlValidatingReader::ReadAttributeValue() override
```

### ค่าที่ส่งคืน

**true** หากมีโหนดที่จะส่งคืน. **false** หากเครื่องอ่านไม่ได้อยู่บนโหนดคุณลักษณะเมื่อทำการเรียกครั้งแรกหรือหากค่าคุณลักษณะทั้งหมดถูกอ่านแล้ว. คุณลักษณะว่างเปล่า เช่น **misc=\"\"** จะคืนค่า **true** พร้อมโหนดเดียวที่มีค่าเป็น [String::Empty](../../../system/string/empty/).

## ดูเพิ่มเติม

* คลาส [XmlValidatingReader](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)