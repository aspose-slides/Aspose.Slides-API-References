---
title: get_BaseURI()
second_title: การอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ส่งคืน Uniform Resource Identifier (URI) พื้นฐานของโหนด.
type: docs
weight: 183
url: /th/system.xml/xmlattribute/get_baseuri/
---
## XmlAttribute::get_BaseURI() เมธอด

ส่งคืน Uniform Resource Identifier (URI) พื้นฐานของโหนด.

```cpp
String System::Xml::XmlAttribute::get_BaseURI() override
```

### ค่าที่คืนค่า

ตำแหน่งที่โหนดถูกโหลดมาหรือ [String::Empty](../../../system/string/empty/) หากโหนดไม่มี base URI. โหนด [Attribute](../../../system/attribute/) มี base URI เดียวกันกับองค์ประกอบเจ้าของของมัน. หากโหนด attribute ไม่ได้มีองค์ประกอบเจ้าของ, get_BaseURI จะส่งคืน [String::Empty](../../../system/string/empty/).

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlAttribute](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)