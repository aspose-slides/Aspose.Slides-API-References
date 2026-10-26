---
title: get_LocalName()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ส่งคืนชื่อท้องถิ่นของโหนดปัจจุบัน.
type: docs
weight: 27
url: /th/system.xml/xmlnodereader/get_localname/
---
## XmlNodeReader::get_LocalName() เมธอด

ส่งคืนชื่อท้องถิ่นของโหนดปัจจุบัน.

```cpp
String System::Xml::XmlNodeReader::get_LocalName() override
```

### ค่าที่ส่งคืน

ชื่อของโหนดปัจจุบันโดยลบคำนำหน้าออก ตัวอย่างเช่น **LocalName** คือ **book** สำหรับองค์ประกอบ **<bk:book>**. สำหรับประเภทโหนดที่ไม่มีชื่อ (เช่น **[Text](../../../system.text/)**, **Comment**, และอื่น ๆ) วิธีนี้จะคืนค่า [String::Empty](../../../system/string/empty/).

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlNodeReader](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)