---
title: InsertElementAfter()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างอีลีเมนต์พี่น้องใหม่หลังจากโหนดปัจจุบันโดยใช้คำนำหน้าพื้นที่ชื่อ ชื่อท้องถิ่น และ URI ของเนมสเปซที่ระบุ พร้อมค่าที่ระบุ.
type: docs
weight: 1028
url: /th/system.xml.xpath/xpathnavigator/insertelementafter/
---
## XPathNavigator::InsertElementAfter(String, String, String, String) เมธอด

สร้างอีลีเมนต์พี่น้องใหม่หลังจากโหนดปัจจุบันโดยใช้คำนำหน้าพื้นที่ชื่อ, ชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุ พร้อมค่าที่ระบุ.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertElementAfter(String prefix, String localName, String namespaceURI, String value)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | คำนำหน้าพื้นที่ชื่อของอีลีเมนต์ลูกใหม่ (ถ้ามี). |
| localName | [String](../../../system/string/) | ชื่อท้องถิ่นของอีลีเมนต์ลูกใหม่ (ถ้ามี). |
| namespaceURI | [String](../../../system/string/) | URI ของเนมสเปซของอีลีเมนต์ลูกใหม่ (ถ้ามี). [String::Empty](../../../system/string/empty/) และ **nullptr** มีค่าเท่ากัน. |
| value | [String](../../../system/string/) | ค่าของอีลีเมนต์ลูกใหม่ หาก [String::Empty](../../../system/string/empty/) หรือ **nullptr** ถูกส่งเข้าไป จะสร้างอีลีเมนต์ว่าง. |

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XPathNavigator](../)
* เนมสเปซ [System::Xml::XPath](../../)
* ไลบรารี [Aspose.Slides](../../../)