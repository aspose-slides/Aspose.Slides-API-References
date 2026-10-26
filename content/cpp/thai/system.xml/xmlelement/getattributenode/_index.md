---
title: GetAttributeNode()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ส่งคืน XmlAttribute ที่มีชื่อที่ระบุ
type: docs
weight: 248
url: /th/system.xml/xmlelement/getattributenode/
---
## XmlElement::GetAttributeNode(String) เมธอด


ส่งคืน [XmlAttribute](../../xmlattribute/) ที่มีชื่อที่ระบุ

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String name)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อของแอตทริบิวต์ที่ต้องการดึงคืน นี่เป็นชื่อที่มีคุณสมบัติครบถ้วน จะเปรียบเทียบกับค่า **get_Name** ของโหนดที่ตรงกัน |

### ค่าที่ส่งคืน

[XmlAttribute](../../xmlattribute/) ที่ระบุหรือ **nullptr** หากไม่พบแอตทริบิวต์ที่ตรงกัน

## XmlElement::GetAttributeNode(String, String) เมธอด


ส่งคืน [XmlAttribute](../../xmlattribute/) ที่มีชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุ

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String localName, String namespaceURI)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | ชื่อท้องถิ่นของแอตทริบิวต์ |
| namespaceURI | [String](../../../system/string/) | URI ของเนมสเปซของแอตทริบิวต์ |

### ค่าที่ส่งคืน

[XmlAttribute](../../xmlattribute/) ที่ระบุหรือ **nullptr** หากไม่พบแอตทริบิวต์ที่ตรงกัน

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlAttribute](../../xmlattribute/)
* คลาส [String](../../../system/string/)
* คลาส [XmlElement](../)
* เนมสเปซ [System::Xml](../../)
* Library [Aspose.Slides](../../../)