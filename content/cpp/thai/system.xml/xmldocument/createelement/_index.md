---
title: CreateElement()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: สร้างอิลิเมนต์ที่มีชื่อที่ระบุ
type: docs
weight: 339
url: /th/system.xml/xmldocument/createelement/
---
## XmlDocument::CreateElement(const String\&) เมธอด


สร้างอิลิเมนต์ที่มีชื่อที่ระบุ

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &name)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | ชื่อที่มีโควาลิฟิเคชันของอิลิเมนต์ ถ้าชื่อมีเครื่องหมายโคลอนค่า [XmlNode::get_Prefix](../../xmlnode/get_prefix/) จะสะท้อนส่วนของชื่อที่อยู่ก่อนเครื่องหมายโคลอนและค่า [XmlDocument::get_LocalName](../get_localname/) จะสะท้อนส่วนของชื่อที่อยู่หลังเครื่องหมายโคลอน ชื่อที่มีโควาลิฟิเคชันไม่สามารถมีคำนำหน้า **xmlns**. |

### ค่าที่คืนกลับ

อ็อบเจ็กต์ใหม่ [XmlElement](../../xmlelement/).

## XmlDocument::CreateElement(const String\&, const String\&) เมธอด


สร้าง [XmlElement](../../xmlelement/) ที่มีชื่อที่มีโควาลิฟิเคชันและ [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/)

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &qualifiedName, const String &namespaceURI)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| qualifiedName | const [String](../../../system/string/)\& | ชื่อที่มีโควาลิฟิเคชันของอิลิเมนต์ ถ้าชื่อมีเครื่องหมายโคลอนค่า [XmlNode::get_Prefix](../../xmlnode/get_prefix/) จะสะท้อนส่วนของชื่อที่อยู่ก่อนเครื่องหมายโคลอนและค่า [XmlDocument::get_LocalName](../get_localname/) จะสะท้อนส่วนของชื่อที่อยู่หลังเครื่องหมายโคลอน ชื่อที่มีโควาลิฟิเคชันไม่สามารถมีคำนำหน้า **xmlns**. |
| namespaceURI | const [String](../../../system/string/)\& | URI ของเนมสเปซของอิลิเมนต์ |

### ค่าที่คืนกลับ

อ็อบเจ็กต์ใหม่ [XmlElement](../../xmlelement/).

## XmlDocument::CreateElement(const String\&, const String\&, const String\&) เมธอด


สร้างอิลิเมนต์ที่มี [XmlNode::get_Prefix](../../xmlnode/get_prefix/) [XmlDocument::get_LocalName](../get_localname/) และ [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) ที่ระบุ

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &prefix, const String &localName, const String &namespaceURI)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | คำนำหน้าของอิลิเมนต์ใหม่ (ถ้ามี) [String::Empty](../../../system/string/empty/) และ **nullptr** มีค่าเท่ากัน. |
| localName | const [String](../../../system/string/)\& | ชื่อท้องถิ่นของอิลิเมนต์ใหม่. |
| namespaceURI | const [String](../../../system/string/)\& | URI ของเนมสเปซของอิลิเมนต์ใหม่ (ถ้ามี) [String::Empty](../../../system/string/empty/) และ **nullptr** มีค่าเท่ากัน. |

### ค่าที่คืนกลับ

อ็อบเจ็กต์ใหม่ [XmlElement](../../xmlelement/).

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlElement](../../xmlelement/)
* คลาส [String](../../../system/string/)
* คลาส [XmlDocument](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)