---
title: get_LocalName()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: เมื่อถูกโอเวอร์ไรด์ในคลาสที่สืบทอด จะรับชื่อท้องถิ่นของโหนดปัจจุบัน
type: docs
weight: 40
url: /th/system.xml/xmlreader/get_localname/
---
## XmlReader::get_LocalName() เมธอด

When overridden in a derived class, gets the local name of the current node.

```cpp
virtual String System::Xml::XmlReader::get_LocalName()=0
```

### ค่าที่ส่งกลับ

The name of the current node with the prefix removed. For example, **LocalName** is **book** for the element **<bk:book>**. For node types that do not have a name (like **[Text](../../../system.text/)**, **Comment**, and so on), this เมธอด returns [String::Empty](../../../system/string/empty/).

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlReader](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)