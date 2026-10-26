---
title: PrependChildElement()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างองค์ประกอบลูกใหม่ที่จุดเริ่มต้นของรายการโหนดลูกของโหนดปัจจุบันโดยใช้คำนำหน้าช่วงชื่อ, ชื่อท้องถิ่น และ URI ของช่วงชื่อที่ระบุพร้อมค่าที่กำหนด
type: docs
weight: 989
url: /th/system.xml.xpath/xpathnavigator/prependchildelement/
---
## XPathNavigator::PrependChildElement(String, String, String, String) เมธอด

สร้างองค์ประกอบลูกใหม่ที่จุดเริ่มต้นของรายการโหนดลูกของโหนดปัจจุบันโดยใช้คำนำหน้าช่วงชื่อ, ชื่อท้องถิ่น, และ URI ของช่วงชื่อที่ระบุพร้อมค่าที่กำหนด

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChildElement(String prefix, String localName, String namespaceURI, String value)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | คำนำหน้าช่วงชื่อขององค์ประกอบลูกใหม่ (ถ้ามี) |
| localName | [String](../../../system/string/) | ชื่อท้องถิ่นขององค์ประกอบลูกใหม่ (ถ้ามี) |
| namespaceURI | [String](../../../system/string/) | URI ของช่วงชื่อขององค์ประกอบลูกใหม่ (ถ้ามี) [String::Empty](../../../system/string/empty/) และ **nullptr** มีค่าเท่ากัน |
| value | [String](../../../system/string/) | ค่าขององค์ประกอบลูกใหม่ หาก [String::Empty](../../../system/string/empty/) หรือ **nullptr** ถูกส่งเข้ามา จะสร้างองค์ประกอบที่ว่างเปล่า |

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XPathNavigator](../)
* เนมสเปซ [System::Xml::XPath](../../)
* ไลบรารี [Aspose.Slides](../../../)