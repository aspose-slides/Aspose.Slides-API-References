---
title: IsStartElement()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "เรียก XmlReader::MoveToContent และทดสอบว่าบล็อกเนื้อหาปัจจุบันเป็นแท็กเริ่มต้นหรือแท็กของอิลเมนต์ว่างหรือไม่."
type: docs
weight: 885
url: /th/system.xml/xmlreader/isstartelement/
---
## XmlReader::IsStartElement() เมธอด

เรียก [XmlReader::MoveToContent](../movetocontent/) และทดสอบว่าบล็อกเนื้อหาปัจจุบันเป็นแท็กเริ่มต้นหรือแท็กของอิลเมนต์ว่างหรือไม่

```cpp
virtual bool System::Xml::XmlReader::IsStartElement()
```

### ค่าที่ส่งกลับ

**true** if [XmlReader::MoveToContent](../movetocontent/) finds a start tag or empty element tag; **false** if a node type other than [XmlNodeType::Element](../../xmlnodetype/) was found.

## XmlReader::IsStartElement(String) เมธอด

เรียก [XmlReader::MoveToContent](../movetocontent/) และทดสอบว่าบล็อกเนื้อหาปัจจุบันเป็นแท็กเริ่มต้นหรือแท็กของอิลเมนต์ว่างและค่าของ [XmlReader::get_Name](../get_name/) ของอิลเมนต์ที่พบตรงกับอาร์กิวเมนต์ที่กำหนด

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String name)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | [String](../../../system/string/) | สตริงที่เปรียบเทียบกับค่าของ **Name** ของอิลเมนต์ที่พบ |

### ค่าที่ส่งกลับ

**true** if the resulting node is an element and the **Name** value matches the specified string. **false** if a node type other than [XmlNodeType::Element](../../xmlnodetype/) was found or if the element **Name** value does not match the specified string.

## XmlReader::IsStartElement(String, String) เมธอด

เรียก [XmlReader::MoveToContent](../movetocontent/) และทดสอบว่าบล็อกเนื้อหาปัจจุบันเป็นแท็กเริ่มต้นหรือแท็กของอิลเมนต์ว่างและค่าของ [XmlReader::get_LocalName](../get_localname/) และ [XmlReader::get_NamespaceURI](../get_namespaceuri/) ของอิลเมนต์ที่พบตรงกับสตริงที่กำหนด

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String localname, String ns)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| localname | [String](../../../system/string/) | สตริงที่เปรียบเทียบกับค่าของ **LocalName** ของอิลเมนต์ที่พบ |
| ns | [String](../../../system/string/) | สตริงที่เปรียบเทียบกับค่าของ **NamespaceURI** ของอิลเมนต์ที่พบ |

### ค่าที่ส่งกลับ

**true** if the resulting node is an element. **false** if a node type other than [XmlNodeType::Element](../../xmlnodetype/) was found or if the **LocalName** and **NamespaceURI** values of the element do not match the specified strings.

## ดูเพิ่มเติม

* คลาส [XmlReader](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)