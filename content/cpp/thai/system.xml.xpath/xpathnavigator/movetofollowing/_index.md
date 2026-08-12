---
title: MoveToFollowing()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ย้าย XPathNavigator ไปยังองค์ประกอบที่มีชื่อท้องถิ่นและ URI ของเนมส페ซที่ระบุในลำดับเอกสาร
type: docs
weight: 703
url: /th/system.xml.xpath/xpathnavigator/movetofollowing/
---
## XPathNavigator::MoveToFollowing(String, String) เมธอด

ย้าย [XPathNavigator](../) ไปยังองค์ประกอบที่มีชื่อท้องถิ่นและ URI ของเนมสเปซตามที่ระบุในลำดับเอกสาร.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| localName | [String](../../../system/string/) | ชื่อท้องถี่ขององค์ประกอบ |
| namespaceURI | [String](../../../system/string/) | URI ของเนมส페ซขององค์ประกอบ |

### ค่าที่ส่งกลับ

**true** หาก [XPathNavigator](../) ถูกย้ายสำเร็จ; มิฉะนั้น **false**.

## XPathNavigator::MoveToFollowing(String, String, SharedPtr\<XPathNavigator\>) เมธอด

ย้าย [XPathNavigator](../) ไปยังองค์ประกอบที่มีชื่อท้องถี่และ URI ของเนมส페ซตามที่ระบุ, ไปยังขอบเขตที่กำหนด, ในลำดับเอกสาร.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI, SharedPtr<XPathNavigator> end)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| localName | [String](../../../system/string/) | ชื่อท้องถี่ขององค์ประกอบ |
| namespaceURI | [String](../../../system/string/) | URI ของเนมส페ซขององค์ประกอบ |
| end | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | วัตถุ [XPathNavigator](../) ที่อยู่บนขอบเขตขององค์ประกอบซึ่ง [XPathNavigator](../) ปัจจุบันจะไม่ขยับเกินขณะค้นหาองค์ประกอบต่อไป |

### ค่าที่ส่งกลับ

**true** หาก [XPathNavigator](../) ถูกย้ายสำเร็จ; มิฉะนั้น **false**.

## XPathNavigator::MoveToFollowing(XPathNodeType) เมธอด

ย้าย [XPathNavigator](../) ไปยังองค์ประกอบต่อไปของ XPathNodeType ที่ระบุในลำดับเอกสาร.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType ขององค์ประกอบ. XPathNodeType ไม่สามารถเป็น [XPathNodeType::Attribute](../../xpathnodetype/) หรือ [XPathNodeType::Namespace](../../xpathnodetype/) |

### ค่าที่ส่งกลับ

**true** หาก [XPathNavigator](../) ถูกย้ายสำเร็จ; มิฉะนั้น **false**.

## XPathNavigator::MoveToFollowing(XPathNodeType, SharedPtr\<XPathNavigator\>) เมธอด

ย้าย [XPathNavigator](../) ไปยังองค์ประกอบต่อไปของ XPathNodeType ที่ระบุ, ไปยังขอบเขตที่กำหนด, ในลำดับเอกสาร.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type, SharedPtr<XPathNavigator> end)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType ขององค์ประกอบ. XPathNodeType ไม่สามารถเป็น [XPathNodeType::Attribute](../../xpathnodetype/) หรือ [XPathNodeType::Namespace](../../xpathnodetype/) |
| end | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | วัตถุ [XPathNavigator](../) ที่อยู่บนขอบเขตขององค์ประกอบซึ่ง [XPathNavigator](../) ปัจจุบันจะไม่ขยับเกินขณะค้นหาองค์ประกอบต่อไป |

### ค่าที่ส่งกลับ

**true** หาก [XPathNavigator](../) ถูกย้ายสำเร็จ; มิฉะนั้น **false**.

## ดูเพิ่มเติม

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [String](../../../system/string/)
* คลาส [XPathNavigator](../)
* เนมส페ซ [System::Xml::XPath](../../)
* ไลบรารี [Aspose.Slides](../../../)