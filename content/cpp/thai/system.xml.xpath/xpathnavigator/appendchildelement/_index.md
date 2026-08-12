---
title: AppendChildElement()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างโหนดองค์ประกอบลูกใหม่ที่ส่วนท้ายของรายการโหนดลูกของโหนดปัจจุบันโดยใช้คำนำหน้าชื่อเนมสเปซ ชื่อท้องถิ่น และ URI ของเนมสเปซที่ระบุพร้อมค่าที่กำหนด.
type: docs
weight: 1002
url: /th/system.xml.xpath/xpathnavigator/appendchildelement/
---
## XPathNavigator::AppendChildElement(String, String, String, String) เมธอด


สร้างโหนดองค์ประกอบลูกใหม่ที่ส่วนท้ายของรายการโหนดลูกของโหนดปัจจุบันโดยใช้คำนำหน้าชื่อเนมสเปซ ชื่อท้องถิ่น และ URI ของเนมสเปซที่ระบุพร้อมค่าที่กำหนด

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChildElement(String prefix, String localName, String namespaceURI, String value)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | คำนำหน้าชื่อเนมสเปซของโหนดลูกใหม่ (ถ้ามี) |
| localName | [String](../../../system/string/) | ชื่อภายในของโหนดลูกใหม่ (ถ้ามี) |
| namespaceURI | [String](../../../system/string/) | URI ของเนมสเปซของโหนดลูกใหม่ (ถ้ามี) [String::Empty](../../../system/string/empty/) และ **nullptr** มีค่าเท่ากัน |
| value | [String](../../../system/string/) | ค่าของโหนดลูกใหม่ หาก [String::Empty](../../../system/string/empty/) หรือ **nullptr** ถูกส่งเข้าไป จะสร้างองค์ประกอบที่ว่างเปล่า |

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XPathNavigator](../)
* เนมสเปซ [System::Xml::XPath](../../)
* ไลบรารี [Aspose.Slides](../../../)