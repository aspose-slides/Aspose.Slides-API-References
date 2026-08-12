---
title: SetAttribute()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: ตั้งค่าค่าของแอตริบิวต์ที่มีชื่อที่ระบุ
type: docs
weight: 222
url: /th/system.xml/xmlelement/setattribute/
---
## XmlElement::SetAttribute(String, String) เมธอด

ตั้งค่าค่าของแอตริบิวต์ที่มีชื่อที่ระบุ

```cpp
virtual void System::Xml::XmlElement::SetAttribute(String name, String value)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อของแอตริบิวต์ที่ต้องการสร้างหรือแก้ไข นี่เป็นชื่อที่มีค.qualifier หากชื่อมีเครื่องหมายโคลอนจะถูกแยกเป็นส่วน prefix และ local name |
| value | [String](../../../system/string/) | ค่าที่จะตั้งให้กับแอตริบิวต์ |

## XmlElement::SetAttribute(String, String, String) เมธอด

ตั้งค่าค่าของแอตริบิวต์ที่มีชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุ

```cpp
virtual String System::Xml::XmlElement::SetAttribute(String localName, String namespaceURI, String value)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| localName | [String](../../../system/string/) | ชื่อท้องถิ่นของแอตริบิวต์ |
| namespaceURI | [String](../../../system/string/) | URI ของเนมสเปซของแอตริบิวต์ |
| value | [String](../../../system/string/) | ค่าที่จะตั้งให้กับแอตริบิวต์ |

### ค่าที่ส่งคืน

ค่าของแอตริบิวต์

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlElement](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)