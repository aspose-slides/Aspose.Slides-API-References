---
title: CreateAttribute()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้างโหนดแอตทริบิวท์บนโหนดอิลิเมนต์ปัจจุบันโดยใช้คำนำหน้าเนมสเปซ, ชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุพร้อมค่าที่กำหนด
type: docs
weight: 1041
url: /th/system.xml.xpath/xpathnavigator/createattribute/
---
## XPathNavigator::CreateAttribute(String, String, String, String) เมธอด

สร้างโหนดแอตทริบิวท์บนโหนดอิลิเมนต์ปัจจุบันโดยใช้คำนำหน้าเนมสเปซ, ชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุพร้อมค่าที่กำหนด

```cpp
virtual void System::Xml::XPath::XPathNavigator::CreateAttribute(String prefix, String localName, String namespaceURI, String value)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | คำนำหน้าเนมสเปซของโหนดแอตทริบิวท์ใหม่ (ถ้ามี). |
| localName | [String](../../../system/string/) | ชื่อท้องถิ่นของโหนดแอตทริบิวท์ใหม่ซึ่งไม่สามารถ [String::Empty](../../../system/string/empty/) หรือ **nullptr**. |
| namespaceURI | [String](../../../system/string/) | URI ของเนมสเปซสำหรับโหนดแอตทริบิวท์ใหม่ (ถ้ามี). |
| value | [String](../../../system/string/) | ค่าของโหนดแอตทริบิวท์ใหม่ หาก [String::Empty](../../../system/string/empty/) หรือ **nullptr** ถูกส่งเข้าไป จะสร้างโหนดแอตทริบิวท์ที่ว่างเปล่า. |

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XPathNavigator](../)
* เนมสเปซ [System::Xml::XPath](../../)
* ไลบรารี [Aspose.Slides](../../../)