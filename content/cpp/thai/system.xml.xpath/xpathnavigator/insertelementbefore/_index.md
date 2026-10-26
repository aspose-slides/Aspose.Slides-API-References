---
title: InsertElementBefore()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้างองค์ประกอบพี่น้องใหม่ก่อนโหนดปัจจุบันโดยใช้คำนำหน้าชื่อเนมสเปซ, ชื่อท้องถิ่น, และ URI ของเนมสเปซที่ระบุ, พร้อมค่าที่ระบุ.
type: docs
weight: 1015
url: /th/system.xml.xpath/xpathnavigator/insertelementbefore/
---
## XPathNavigator::InsertElementBefore(String, String, String, String) method

สร้างองค์ประกอบพี่น้องใหม่ก่อนโหนดปัจจุบันโดยใช้คำนำหน้าชื่อเนมสเปซ, ชื่อท้องถิ่น, และ URI ของเนมสเปซที่ระบุ, พร้อมค่าที่ระบุ.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertElementBefore(String prefix, String localName, String namespaceURI, String value)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | คำนำหน้าชื่อเนมสเปซขององค์ประกอบลูกใหม่ (หากมี). |
| localName | [String](../../../system/string/) | ชื่อท้องถิ่นขององค์ประกอบลูกใหม่ (หากมี). |
| namespaceURI | [String](../../../system/string/) | URI ของเนมสเปซขององค์ประกอบลูกใหม่ (หากมี). [String::Empty](../../../system/string/empty/) และ **nullptr** มีค่าเท่ากัน. |
| value | [String](../../../system/string/) | ค่าขององค์ประกอบลูกใหม่ หาก [String::Empty](../../../system/string/empty/) หรือ **nullptr** ถูกส่งเข้ามา จะสร้างองค์ประกอบว่างเปล่า. |

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XPathNavigator](../)
* เนมสเปซ [System::Xml::XPath](../../)
* ไลบรารี [Aspose.Slides](../../../)