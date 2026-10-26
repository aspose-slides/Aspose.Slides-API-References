---
title: LookupNamespace()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เมื่อถูกเขียนทับในคลาสที่สืบทอด จะทำการแก้ไขคำนำหน้าของ namespace ในขอบเขตของเอลิเมนต์ปัจจุบัน
type: docs
weight: 729
url: /th/system.xml/xmlreader/lookupnamespace/
---
## XmlReader::LookupNamespace(const String\&) เมธอด


When overridden in a derived class, resolves a namespace prefix in the current element's scope.

```cpp
virtual String System::Xml::XmlReader::LookupNamespace(const String &prefix)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | prefix ที่คุณต้องการแก้ไข namespace URI. เพื่อให้ตรงกับ namespace เริ่มต้น ให้ส่งสตริงว่าง. |

### ค่าที่ส่งกลับ

URI ของ namespace ที่ prefix ถูกแมพไป หรือ **nullptr** หากไม่พบ prefix ที่ตรงกัน.

## ดูเพิ่มเติม

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)