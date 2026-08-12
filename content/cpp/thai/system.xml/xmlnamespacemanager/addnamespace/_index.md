---
title: AddNamespace()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: เพิ่มเนมสเปซที่กำหนดให้กับคอลเลกชัน.
type: docs
weight: 66
url: /th/system.xml/xmlnamespacemanager/addnamespace/
---
## XmlNamespaceManager::AddNamespace(String, String) เมธอด

เพิ่มเนมสเปซที่กำหนดให้กับคอลเลกชัน

```cpp
virtual void System::Xml::XmlNamespaceManager::AddNamespace(String prefix, String uri)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | คำนำหน้าที่จะเชื่อมโยงกับเนมสเปซที่กำลังเพิ่ม. ใช้ [String::Empty](../../../system/string/empty/) เพื่อเพิ่มเนมสเปซเริ่มต้น. หาก [XmlNamespaceManager](../) จะถูกใช้ในการแก้ไขเนมสเปซในนิพจน์ XML Path Language ([XPath](../../../system.xml.xpath/)) ต้องระบุคำนำหน้า. หากนิพจน์ [XPath](../../../system.xml.xpath/) ไม่รวมคำนำหน้า จะถือว่า Uniform Resource Identifier (URI) ของเนมสเปซเป็นเนมสเปซเปล่า. สำหรับข้อมูลเพิ่มเติมเกี่ยวกับนิพจน์ [XPath](../../../system.xml.xpath/) และ [XmlNamespaceManager](../) ให้ดูที่เมธอด XmlNode::SelectNodes(String) และ XPathExpression::SetContext(SharedPtr<XmlNamespaceManager>) |
| uri | [String](../../../system/string/) | เนมสเปซที่ต้องการเพิ่ม. |

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlNamespaceManager](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)