---
title: GetAttribute()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ส่งคืนค่าของแอตทริบิวต์ที่มีชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุ
type: docs
weight: 482
url: /th/system.xml.xpath/xpathnavigator/getattribute/
---
## XPathNavigator::GetAttribute(String, String) เมธอด

Returns the value of the attribute with the specified local name and namespace URI.

```cpp
virtual String System::Xml::XPath::XPathNavigator::GetAttribute(String localName, String namespaceURI)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | The local name of the attribute. **localName** is case-sensitive. |
| namespaceURI | [String](../../../system/string/) | The namespace URI of the attribute. |

### ค่าที่ส่งคืน

A [String](../../../system/string/) that contains the value of the specified attribute; [String::Empty](../../../system/string/empty/) if a matching attribute is not found, or if the [XPathNavigator](../) is not positioned on an element node.

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XPathNavigator](../)
* เนมสเปซ [System::Xml::XPath](../../)
* ไลบรารี [Aspose.Slides](../../../)