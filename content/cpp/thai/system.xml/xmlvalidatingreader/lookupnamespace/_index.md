---
title: LookupNamespace()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แก้ไขคำนำหน้าชื่อเนมสเปซในขอบเขตขององค์ประกอบปัจจุบัน.
type: docs
weight: 547
url: /th/system.xml/xmlvalidatingreader/lookupnamespace/
---
## XmlValidatingReader::LookupNamespace(const String\&) เมธอด


แก้ไขคำนำหน้าชื่อเนมสเปซในขอบเขตขององค์ประกอบปัจจุบัน.

```cpp
String System::Xml::XmlValidatingReader::LookupNamespace(const String &prefix) override
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | คำนำหน้าที่คุณต้องการค้นหา Uniform Resource Identifier (URI) ของเนมสเปซนั้น. หากต้องการจับคู่กับเนมสเปซเริ่มต้น ให้ส่งสตริงว่าง. |

### ค่าที่คืน

URI ของเนมสเปซที่คำนำหน้าจับคู่อยู่ หรือ **nullptr** หากไม่พบคำนำหน้าที่ตรงกัน.

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlValidatingReader](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)