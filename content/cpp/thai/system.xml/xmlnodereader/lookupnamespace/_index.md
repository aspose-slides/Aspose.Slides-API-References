---
title: LookupNamespace()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แก้ไขคำนำหน้าชื่อเนมส페ซในสโคปขององค์ประกอบปัจจุบัน.
type: docs
weight: 404
url: /th/system.xml/xmlnodereader/lookupnamespace/
---
## XmlNodeReader::LookupNamespace(const String\&) เมธอด


แก้ไขคำนำหน้าชื่อเนมส페ซในสโคปขององค์ประกอบปัจจุบัน.

```cpp
String System::Xml::XmlNodeReader::LookupNamespace(const String &prefix) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | คำนำหน้าที่คุณต้องการแก้ไข URI ของเนมส페ซ. เพื่อให้ตรงกับเนมส페ซเริ่มต้น ให้ส่งสตริงว่าง. สตริงนี้ไม่จำเป็นต้องเป็น atomized. |

### ค่าที่ส่งคืน

URI ของเนมส페ซที่คำนำหน้าแมพไปหรือ **nullptr** หากไม่พบคำนำหน้าที่ตรงกัน.

## ดูเพิ่มเติม

* Class [String](../../../system/string/)
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)