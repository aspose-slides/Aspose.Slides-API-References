---
title: CreateNode()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "สร้าง XmlNode ด้วย XmlNodeType ที่ระบุ, XmlNode::get_Prefix, XmlDocument::get_Name และ XmlNode::get_NamespaceURI."
type: docs
weight: 482
url: /th/system.xml/xmldocument/createnode/
---
## XmlDocument::CreateNode(XmlNodeType, const String&, const String&, const String&) method

สร้าง [XmlNode](../../xmlnode/) ด้วย XmlNodeType ที่ระบุ, [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_Name](../get_name/) และ [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &prefix, const String &name, const String &namespaceURI)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| type | [XmlNodeType](../../xmlnodetype/) | XmlNodeType ของโหนดใหม่ |
| prefix | const [String](../../../system/string/)& | คำนำหน้าของโหนดใหม่ |
| name | const [String](../../../system/string/)& | ชื่อในท้องถิ่นของโหนดใหม่ |
| namespaceURI | const [String](../../../system/string/)& | URI ของเนมสเปซของโหนดใหม่ |

### ค่าที่คืน

[XmlNode](../../xmlnode/) ใหม่.

## XmlDocument::CreateNode(const String&, const String&, const String&) method

สร้าง [XmlNode](../../xmlnode/) ด้วยประเภทโหนดที่ระบุ, [XmlDocument::get_Name](../get_name/) และ [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(const String &nodeTypeString, const String &name, const String &namespaceURI)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| nodeTypeString | const [String](../../../system/string/)& | เวอร์ชัน [String](../../../system/string/) ของ XmlNodeType ของโหนดใหม่ พารามิเตอร์นี้ต้องเป็นหนึ่งในค่าที่ระบุในตารางด้านล่าง |
| name | const [String](../../../system/string/)& | ชื่อแบบเต็มของโหนดใหม่ หากชื่อมีเครื่องหมายโคลอน จะถูกแยกเป็นส่วนประกอบ [XmlNode::get_Prefix](../../xmlnode/get_prefix/) และ [XmlDocument::get_LocalName](../get_localname/) |
| namespaceURI | const [String](../../../system/string/)& | URI ของเนมสเปซของโหนดใหม่ |

### ค่าที่คืน

[XmlNode](../../xmlnode/) ใหม่.

## หมายเหตุ

พารามิเตอร์ **nodeTypeString** มีความแตกต่างของตัวพิมพ์และต้องเป็นหนึ่งในค่าที่อยู่ในตารางต่อไปนี้: 

| nodeTypeString| XmlNodeType |
| --- | --- |
| attribute| [Attribute](../../../system/attribute/)|
| cdatasection| CDATA |
| comment| Comment |
| document| Document |
| documentfragment| DocumentFragment |
| documenttype| DocumentType |
| element| Element |
| entityreference| EntityReference |
| processinginstruction| ProcessingInstruction |
| significantwhitespace| SignificantWhitespace |
| text| [Text](../../../system.text/)|
| whitespace| Whitespace |

## XmlDocument::CreateNode(XmlNodeType, const String&, const String&) method

สร้าง [XmlNode](../../xmlnode/) ด้วย XmlNodeType ที่ระบุ, [XmlDocument::get_Name](../get_name/) และ [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &name, const String &namespaceURI)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| type | [XmlNodeType](../../xmlnodetype/) | XmlNodeType ของโหนดใหม่ |
| name | const [String](../../../system/string/)& | ชื่อแบบเต็มของโหนดใหม่ หากชื่อมีเครื่องหมายโคลอน จะถูกแยกเป็นส่วนประกอบ [XmlNode::get_Prefix](../../xmlnode/get_prefix/) และ [XmlDocument::get_LocalName](../get_localname/) |
| namespaceURI | const [String](../../../system/string/)& | URI ของเนมสเปซของโหนดใหม่ |

### ค่าที่คืน

[XmlNode](../../xmlnode/) ใหม่.

## ดูเพิ่มเติม

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)