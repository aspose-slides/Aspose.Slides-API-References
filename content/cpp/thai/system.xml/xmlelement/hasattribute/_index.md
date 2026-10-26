---
title: HasAttribute()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: กำหนดว่าตำแหน่งปัจจุบันมีแอตทริบิวต์ที่มีชื่อที่ระบุหรือไม่.
type: docs
weight: 300
url: /th/system.xml/xmlelement/hasattribute/
---
## XmlElement::HasAttribute(String) เมธอด

กำหนดว่าตำแหน่งปัจจุบันมีแอตทริบิวต์ที่มีชื่อที่ระบุหรือไม่.

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String name)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อของแอตทริบิวต์ที่ต้องการค้นหา ซึ่งเป็นชื่อที่มีการระบุเต็มรูปแบบ จะเทียบกับค่า **get_Name** ของโหนดที่ตรงกัน. |

### ค่าที่ส่งกลับ

**true** หากตำแหน่งปัจจุบันมีแอตทริบิวต์ที่ระบุ; มิฉะนั้น **false**.

## XmlElement::HasAttribute(String, String) เมธอด

กำหนดว่าตำแหน่งปัจจุบันมีแอตทริบิวต์ที่มีชื่อท้องถิ่นและ URI ชื่อเนมสเปซที่ระบุหรือไม่.

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String localName, String namespaceURI)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| localName | [String](../../../system/string/) | ชื่อท้องถิ่นของแอตทริบิวต์ที่ต้องการค้นหา. |
| namespaceURI | [String](../../../system/string/) | URI ของชื่อเนมสเปซของแอตทริบิวต์ที่ต้องการค้นหา. |

### ค่าที่ส่งกลับ

**true** หากตำแหน่งปัจจุบันมีแอตทริบิวต์ที่ระบุ; มิฉะนั้น **false**.

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlElement](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)