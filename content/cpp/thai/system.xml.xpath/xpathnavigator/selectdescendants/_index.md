---
title: SelectDescendants()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เลือกโหนดทายาททั้งหมดของโหนดปัจจุบันที่มี XPathNodeType ตรงกัน.
type: docs
weight: 859
url: /th/system.xml.xpath/xpathnavigator/selectdescendants/
---
## XPathNavigator::SelectDescendants(XPathNodeType, bool) เมธอด

เลือกโหนดทายาททั้งหมดของโหนดปัจจุบันที่มี XPathNodeType ตรงกัน.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(XPathNodeType type, bool matchSelf)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType ของโหนดทายาท |
| matchSelf | **bool** | **true** เพื่อรวมโหนดบริบทในการเลือก; มิฉะนั้น **false**. |

### ค่าที่คืน

[XPathNodeIterator](../../xpathnodeiterator/) ที่มีโหนดที่เลือก

## XPathNavigator::SelectDescendants(String, String, bool) เมธอด

เลือกโหนดทายาททั้งหมดของโหนดปัจจุบันที่มีชื่อท้องถิ่นและ namespace URI ที่ระบุ.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(String name, String namespaceURI, bool matchSelf)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อท้องถิ่นของโหนดทายาท |
| namespaceURI | [String](../../../system/string/) | namespace URI ของโหนดทายาท |
| matchSelf | **bool** | **true** เพื่อรวมโหนดบริบทในการเลือก; มิฉะนั้น **false**. |

### ค่าที่คืน

[XPathNodeIterator](../../xpathnodeiterator/) ที่มีโหนดที่เลือก

## ดูเพิ่มเติม

* เอนัม [XPathNodeType](../../xpathnodetype/)
* ชนิดกำหนด [SharedPtr](../../../system/sharedptr/)
* คลาส [XPathNodeIterator](../../xpathnodeiterator/)
* คลาส [XPathNavigator](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [System::Xml::XPath](../../)
* ไลบรารี [Aspose.Slides](../../../)