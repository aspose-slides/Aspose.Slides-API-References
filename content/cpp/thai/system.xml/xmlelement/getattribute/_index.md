---
title: GetAttribute()
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: คืนค่าของแอตทริบิวต์ที่มีชื่อที่ระบุ
type: docs
weight: 209
url: /th/system.xml/xmlelement/getattribute/
---
## XmlElement::GetAttribute(String) เมธอด

คืนค่าของแอตทริบิวต์ที่มีชื่อที่ระบุ.

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String name)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อของแอตทริบิวต์ที่ต้องการดึง. นี่คือชื่อที่มีคุณสมบัติครบถ้วน. จะเปรียบเทียบกับค่า **get_Name** ของโหนดที่ตรงกัน. |

### ค่าที่ส่งคืน

ค่ของแอตทริบิวต์ที่ระบุ. จะส่งคืนสตริงว่างหากไม่พบแอตทริบิวต์ที่ตรงกันหรือหากแอตทริบิวต์ไม่มีค่าใดที่ระบุหรือค่าเริ่มต้น.

## XmlElement::GetAttribute(String, String) เมธอด

คืนค่าของแอตทริบิวต์ที่มีชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุ.

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String localName, String namespaceURI)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| localName | [String](../../../system/string/) | ชื่อท้องถิ่นของแอตทริบิวต์ที่ต้องการดึง. |
| namespaceURI | [String](../../../system/string/) | URI ของเนมสเปซของแอตทริบิวต์ที่ต้องการดึง. |

### ค่าที่ส่งคืน

ค่ของแอตทริบิวต์ที่ระบุ. จะส่งคืนสตริงว่างหากไม่พบแอตทริบิวต์ที่ตรงกันหรือหากแอตทริบิวต์ไม่มีค่าใดที่ระบุหรือค่าเริ่มต้น.

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlElement](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)