---
title: SetAttributeNode()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เพิ่ม XmlAttribute ที่ระบุ
type: docs
weight: 261
url: /th/system.xml/xmlelement/setattributenode/
---
## XmlElement::SetAttributeNode(SharedPtr\<XmlAttribute\>) เมธอด

เพิ่ม [XmlAttribute](../../xmlattribute/) ที่ระบุ

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(SharedPtr<XmlAttribute> newAttr)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| newAttr | [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\> | โหนด [XmlAttribute](../../xmlattribute/) ที่จะเพิ่มเข้าไปในคอลเลกชันแอตทริบิวต์สำหรับเอลีเมนต์นี้ |

### ค่าที่ส่งกลับ

หากแอตทริบิวต์แทนที่แอตทริบิวต์ที่มีอยู่ซึ่งมีชื่อเดียวกัน, [XmlAttribute](../../xmlattribute/) เก่าจะถูกส่งกลับ; ไม่เช่นนั้น, **nullptr** จะถูกส่งกลับ

## XmlElement::SetAttributeNode(String, String) เมธอด

เพิ่ม [XmlAttribute](../../xmlattribute/) ที่ระบุ

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(String localName, String namespaceURI)
```

### อาร์กิวเม้นต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| localName | [String](../../../system/string/) | ชื่อโลคัลของแอตทริบิวต์ |
| namespaceURI | [String](../../../system/string/) | URI ของเนมสเปซของแอตทริบิวต์ |

### ค่าที่ส่งกลับ

[XmlAttribute](../../xmlattribute/) ที่จะเพิ่ม

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlAttribute](../../xmlattribute/)
* คลาส [XmlElement](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)