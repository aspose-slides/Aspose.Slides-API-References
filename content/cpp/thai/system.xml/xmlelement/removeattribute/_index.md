---
title: RemoveAttribute()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ลบแอตทริบิวต์โดยใช้ชื่อ.
type: docs
weight: 235
url: /th/system.xml/xmlelement/removeattribute/
---
## XmlElement::RemoveAttribute(String) เมธอด


ลบแอตทริบิวต์โดยใช้ชื่อ

```cpp
virtual void System::Xml::XmlElement::RemoveAttribute(String name)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อของแอตทริบิวต์ที่ต้องการลบ นี่เป็นชื่อที่มีคุณสมบัติครบถ้วน จะทำการจับคู่กับค่า **get_Name** ของโหนดที่ตรงกัน |

## XmlElement::RemoveAttribute(String, String) เมธอด


ลบแอตทริบิวต์ด้วยชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุ (หากแอตทริบิวต์ที่ลบมีค่าตั้งต้น จะถูกแทนที่โดยทันที)

```cpp
virtual void System::Xml::XmlElement::RemoveAttribute(String localName, String namespaceURI)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| localName | [String](../../../system/string/) | ชื่อท้องถิ่นของแอตทริบิวต์ที่ต้องการลบ |
| namespaceURI | [String](../../../system/string/) | URI ของเนมสเปซของแอตทริบิวต์ที่ต้องการลบ |

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlElement](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)