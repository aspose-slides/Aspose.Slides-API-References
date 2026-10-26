---
title: LookupNamespace()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แก้ไขพรีฟิกซ์ของเนมสเปซในขอบเขตขององค์ประกอบปัจจุบัน.
type: docs
weight: 612
url: /th/system.xml/xmltextreader/lookupnamespace/
---
## XmlTextReader::LookupNamespace(const String\&) เมธอด


ทำการแก้ไขพรีฟิกซ์ของเนมสเปซในขอบเขตขององค์ประกอบปัจจุบัน.

```cpp
String System::Xml::XmlTextReader::LookupNamespace(const String &prefix) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | พรีฟิกซ์ที่คุณต้องการแก้ไข URI ของเนมสเปซ. เพื่อให้ตรงกับเนมสเปซเริ่มต้น ให้ส่งสตริงว่าง. สตริงนี้ไม่จำเป็นต้องเป็น atomized. |

### ค่าที่คืนกลับ

URI ของเนมสเปซที่พรีฟิกซ์แมปไปหรือ **nullptr** หากไม่พบพรีฟิกซ์ที่ตรงกัน.

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlTextReader](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)