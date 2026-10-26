---
title: get_LocalName()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: ส่งคืนชื่อภายในของโหนดปัจจุบัน.
type: docs
weight: 27
url: /th/system.xml/xmlvalidatingreader/get_localname/
---
## XmlValidatingReader::get_LocalName() เมธอด


ส่งคืนชื่อภายในของโหนดปัจจุบัน.

```cpp
String System::Xml::XmlValidatingReader::get_LocalName() override
```


### ค่าที่ส่งคืน

ชื่อของโหนดปัจจุบันโดยลบคำนำหน้าออก ตัวอย่างเช่น **LocalName** คือ **book** สำหรับองค์ประกอบ **<bk:book>**. สำหรับประเภทโหนดที่ไม่มีชื่อ (เช่น **[Text](../../../system.text/)**, **Comment**, เป็นต้น) วิธีการนี้จะคืนค่า [String::Empty](../../../system/string/empty/).

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlValidatingReader](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)