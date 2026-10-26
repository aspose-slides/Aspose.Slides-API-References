---
title: MoveToChild()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ย้าย XPathNavigator ไปยังโหนดลูกที่มีชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุ
type: docs
weight: 690
url: /th/system.xml.xpath/xpathnavigator/movetochild/
---
## XPathNavigator::MoveToChild(String, String) เมธอด


ย้าย [XPathNavigator](../) ไปยังโหนดลูกที่มีชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุ.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(String localName, String namespaceURI)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| localName | [String](../../../system/string/) | ชื่อท้องถิ่นของโหนดลูกที่จะย้ายไป |
| namespaceURI | [String](../../../system/string/) | URI ของเนมสเปซของโหนดลูกที่จะย้ายไป |

### ค่าที่ส่งกลับ

**true** หาก [XPathNavigator](../) ย้ายไปยังโหนดลูกสำเร็จ; มิฉะนั้น **false**. หาก **false**, ตำแหน่งของ [XPathNavigator](../) จะไม่เปลี่ยนแปลง.

## XPathNavigator::MoveToChild(XPathNodeType) เมธอด


ย้าย [XPathNavigator](../) ไปยังโหนดลูกของ XPathNodeType ที่ระบุ.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(XPathNodeType type)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | XPathNodeType ของโหนดลูกที่จะย้ายไป |

### ค่าที่ส่งกลับ

**true** หาก [XPathNavigator](../) ย้ายไปยังโหนดลูกสำเร็จ; มิฉะนั้น **false**. หาก **false**, ตำแหน่งของ [XPathNavigator](../) จะไม่เปลี่ยนแปลง.

## ดูเพิ่มเติม

* Enum [XPathNodeType](../../xpathnodetype/)
* คลาส [String](../../../system/string/)
* คลาส [XPathNavigator](../)
* เนมสเปซ [System::Xml::XPath](../../)
* ไลบรารี [Aspose.Slides](../../../)