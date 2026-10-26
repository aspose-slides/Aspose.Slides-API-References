---
title: CreateAttribute()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้าง XmlAttribute ด้วยชื่อที่ระบุ.
type: docs
weight: 274
url: /th/system.xml/xmldocument/createattribute/
---
## XmlDocument::CreateAttribute(const String\&) เมธอด


สร้าง [XmlAttribute](../../xmlattribute/) ด้วยชื่อที่ระบุ.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &name)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | ชื่อที่มีคุณสมบัติของแอตทริบิวต์ หากชื่อมีเครื่องหมายโคลอน ค่าของ [XmlNode::get_Prefix](../../xmlnode/get_prefix/) จะสะท้อนส่วนของชื่อที่อยู่ก่อนโคลอนตัวแรก และค่าของ [XmlDocument::get_LocalName](../get_localname/) จะสะท้อนส่วนของชื่อที่อยู่หลังโคลอนตัวแรก [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) จะว่างเปล่าเว้นแต่คำนำหน้าเป็นคำนำหน้าที่รู้จักในตัวอย่างเช่น **xmlns** ในกรณีนี้ get_NamespaceURI จะมีค่าเป็น [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/). |

### ค่าที่ส่งคืน

[XmlAttribute](../../xmlattribute/) ใหม่.

## XmlDocument::CreateAttribute(const String\&, const String\&) เมธอด


สร้าง [XmlAttribute](../../xmlattribute/) ด้วยชื่อที่มีคุณสมบัติที่ระบุและ [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &qualifiedName, const String &namespaceURI)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| qualifiedName | const [String](../../../system/string/)\& | ชื่อที่มีคุณสมบัติของแอตทริบิวต์ หากชื่อมีเครื่องหมายโคลอนแล้วค่าของ [XmlNode::get_Prefix](../../xmlnode/get_prefix/) จะสะท้อนส่วนของชื่อที่อยู่ก่อนโคลอนและค่าของ [XmlDocument::get_LocalName](../get_localname/) จะสะท้อนส่วนของชื่อที่อยู่หลังโคลอนไป. |
| namespaceURI | const [String](../../../system/string/)\& | namespaceURI ของแอตทริบิวต์ หากชื่อที่มีคุณสมบัติรวมคำนำหน้า **xmlns** แล้วพารามิเตอร์นี้ต้องเป็น [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/). |

### ค่าที่ส่งคืน

[XmlAttribute](../../xmlattribute/) ใหม่.

## XmlDocument::CreateAttribute(const String\&, const String\&, const String\&) เมธอด


สร้าง [XmlAttribute](../../xmlattribute/) ด้วย [XmlNode::get_Prefix](../../xmlnode/get_prefix/) [XmlDocument::get_LocalName](../get_localname/) และ [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) ที่ระบุ.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &prefix, const String &localName, const String &namespaceURI)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | คำนำหน้าของแอตทริบิวต์ (ถ้ามี) [String::Empty](../../../system/string/empty/) และ **nullptr** มีค่าเท่ากัน. |
| localName | const [String](../../../system/string/)\& | ชื่อท้องถิ่นของแอตทริบิวต์. |
| namespaceURI | const [String](../../../system/string/)\& | namespace URI ของแอตทริบิวต์ (ถ้ามี) [String::Empty](../../../system/string/empty/) และ **nullptr** มีค่าเท่ากัน หาก **prefix** เป็น **xmlns** แล้วพารามิเตอร์นี้ต้องเป็น [http://www.w3.org/2000/xmlns/;](http://www.w3.org/2000/xmlns/;) ไม่เช่นนั้นจะเกิดข้อยกเว้น. |

### ค่าที่ส่งคืน

[XmlAttribute](../../xmlattribute/) ใหม่.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlAttribute](../../xmlattribute/)
* คลาส [String](../../../system/string/)
* คลาส [XmlDocument](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)