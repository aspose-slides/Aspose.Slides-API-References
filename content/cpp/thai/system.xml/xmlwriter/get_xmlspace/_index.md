---
title: get_XmlSpace()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "เมื่อทำการ override ในคลาสที่สืบทอด จะได้รับ XmlSpace ที่เป็นตัวแทนของขอบเขต xml:space ปัจจุบัน."
type: docs
weight: 27
url: /th/system.xml/xmlwriter/get_xmlspace/
---
## XmlWriter::get_XmlSpace() เมธอด


When overridden in a derived class, gets an XmlSpace representing the current **xml:space** scope.

```cpp
virtual System::Xml::XmlSpace System::Xml::XmlWriter::get_XmlSpace()
```


### ค่าที่ส่งกลับ

XmlSpace ที่เป็นตัวแทนของขอบเขต **xml:space** ปัจจุบัน.



| ค่า | ความหมาย |
| --- | --- |
| `None`| นี้เป็นค่าเริ่มต้นถ้าไม่มีขอบเขต `xml:space` อยู่ |
| `Default`| ขอบเขตปัจจุบันคือ `xml:space="default"` |
| `Preserve`| ขอบเขตปัจจุบันคือ `xml:space="preserve"` |


## ดูเพิ่มเติม

* Enum [XmlSpace](../../xmlspace/)
* คลาส [XmlWriter](../)
* เนมสเปซ [System::Xml](../../)
* Library [Aspose.Slides](../../../)