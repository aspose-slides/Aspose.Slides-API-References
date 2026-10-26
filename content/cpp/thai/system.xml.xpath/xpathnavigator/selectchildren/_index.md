---
title: SelectChildren()
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: เลือกโหนดลูกทั้งหมดของโหนดปัจจุบันที่มี XPathNodeType ตรงกับที่กำหนด
type: docs
weight: 833
url: /th/system.xml.xpath/xpathnavigator/selectchildren/
---
## XPathNavigator::SelectChildren(XPathNodeType) เมธอด

เลือกโหนดลูกทั้งหมดของโหนดปัจจุบันที่มี XPathNodeType ที่ตรงกัน.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(XPathNodeType type)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType ของโหนดลูก |

### ค่าที่ส่งกลับ

อ็อบเจกต์ [XPathNodeIterator](../../xpathnodeiterator/) ที่เก็บโหนดที่เลือกไว้.

## XPathNavigator::SelectChildren(String, String) เมธอด

เลือกโหนดลูกทั้งหมดของโหนดปัจจุบันที่มีชื่อท้องถิ่นและ URI ของเนมสเปซตามที่ระบุ.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(String name, String namespaceURI)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อท้องถิ่นของโหนดลูก |
| namespaceURI | [String](../../../system/string/) | URI ของเนมสเปซของโหนดลูก |

### ค่าที่ส่งกลับ

อ็อบเจกต์ [XPathNodeIterator](../../xpathnodeiterator/) ที่เก็บโหนดที่เลือกไว้.

## ดูเพิ่มเติม

* enum [XPathNodeType](../../xpathnodetype/)
* typedef [SharedPtr](../../../system/sharedptr/)
* class [XPathNodeIterator](../../xpathnodeiterator/)
* class [XPathNavigator](../)
* class [String](../../../system/string/)
* namespace [System::Xml::XPath](../../)
* library [Aspose.Slides](../../../)