---
title: GetNamedItem()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ดึง XmlNode ที่ระบุโดยชื่อ.
type: docs
weight: 14
url: /th/system.xml/xmlnamednodemap/getnameditem/
---
## XmlNamedNodeMap::GetNamedItem(String) เมธอด

ดึงข้อมูล [XmlNode](../../xmlnode/) ที่ระบุโดยชื่อ

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String name)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อที่สมบูรณ์ของโหนดที่ต้องการดึง ค่าจะถูกเปรียบเทียบกับค่า [XmlNode::get_Name](../../xmlnode/get_name/) ของโหนดที่ตรงกัน |

### ค่าที่คืนกลับ

[XmlNode](../../xmlnode/) ที่มีชื่อที่ระบุ หรือ **nullptr** หากไม่พบโหนดที่ตรงกัน

## XmlNamedNodeMap::GetNamedItem(String, String) เมธอด

ดึงโหนดที่มีค่า [XmlNode::get_LocalName](../../xmlnode/get_localname/) และ [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) ที่ตรงกัน

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String localName, String namespaceURI)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| localName | [String](../../../system/string/) | ชื่อท้องถิ่นของโหนดที่ต้องการดึง |
| namespaceURI | [String](../../../system/string/) | Uniform Resource Identifier (URI) ของ namespace ของโหนดที่ต้องการดึง |

### ค่าที่คืนกลับ

[XmlNode](../../xmlnode/) ที่มีชื่อท้องถิ่นและ namespace URI ตรงกัน หรือ **nullptr** หากไม่พบโหนดที่ตรงกัน

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlNode](../../xmlnode/)
* คลาส [String](../../../system/string/)
* คลาส [XmlNamedNodeMap](../)
* เนมสเปซ [System::Xml](../../)
* Library [Aspose.Slides](../../../)