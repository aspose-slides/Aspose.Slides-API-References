---
title: SelectAncestors()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: เลือกโหนดบรรพบุรุษทั้งหมดของโหนดปัจจุบันที่มี XPathNodeType ตรงกัน.
type: docs
weight: 846
url: /th/system.xml.xpath/xpathnavigator/selectancestors/
---
## XPathNavigator::SelectAncestors(XPathNodeType, bool) เมธอด

เลือกโหนดบรรพบุรุษทั้งหมดของโหนดปัจจุบันที่มี XPathNodeType ที่ตรงกัน.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(XPathNodeType type, bool matchSelf)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType ของโหนดบรรพบุรุษ |
| matchSelf | **bool** | เพื่อรวมโหนดบริบทในการเลือก, **true**; มิฉะนั้น **false**. |

### ค่าที่ส่งคืน

เป็น [XPathNodeIterator](../../xpathnodeiterator/) ที่บรรจุโหนดที่เลือก. โหนดที่ส่งคืนอยู่ในลำดับเอกสารย้อนกลับ.

## XPathNavigator::SelectAncestors(String, String, bool) เมธอด

เลือกโหนดบรรพบุรุษทั้งหมดของโหนดปัจจุบันที่มีชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุ.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(String name, String namespaceURI, bool matchSelf)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อท้องถิ่นของโหนดบรรพบุรุษ |
| namespaceURI | [String](../../../system/string/) | URI ของเนมสเปซของโหนดบรรพบุรุษ |
| matchSelf | **bool** | เพื่อรวมโหนดบริบทในการเลือก, **true**; มิฉะนั้น **false**. |

### ค่าที่ส่งคืน

เป็น [XPathNodeIterator](../../xpathnodeiterator/) ที่บรรจุโหนดที่เลือก. โหนดที่ส่งคืนอยู่ในลำดับเอกสารย้อนกลับ.

## ดูเพิ่มเติม

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XPathNodeIterator](../../xpathnodeiterator/)
* คลาส [XPathNavigator](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [System::Xml::XPath](../../)
* ไลบรารี [Aspose.Slides](../../../)