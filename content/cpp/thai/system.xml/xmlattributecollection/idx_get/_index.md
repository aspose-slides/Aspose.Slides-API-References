---
title: idx_get()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ส่งคืนแอตทริบิวต์ที่มีดัชนีตามที่ระบุ.
type: docs
weight: 1
url: /th/system.xml/xmlattributecollection/idx_get/
---
## XmlAttributeCollection::idx_get(int32_t) เมธอด


ส่งคืนแอตทริบิวต์ที่มีดัชนีตามที่ระบุ.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(int32_t i)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| i | **int32_t** | ดัชนีของแอตทริบิวต์. |

### ค่าที่ส่งกลับ

แอตทริบิวต์ที่ตำแหน่งดัชนีที่ระบุ.

## XmlAttributeCollection::idx_get(const String\&) เมธอด


ส่งคืนแอตทริบิวต์ที่มีชื่อตามที่ระบุ.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &name)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | ชื่อที่สมบูรณ์ของแอตทริบิวต์. |

### ค่าที่ส่งกลับ

แอตทริบิวต์ที่มีชื่อตามที่ระบุ หากแอตทริบิวต์ไม่มีอยู่ เมธอดนี้จะส่งคืน **nullptr**.

## XmlAttributeCollection::idx_get(const String\&, const String\&) เมธอด


ส่งคืนแอตทริบิวต์ที่มีชื่อท้องถิ่นและ Uniform Resource Identifier (URI) ของเนมสเปซตามที่ระบุ.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &localName, const String &namespaceURI)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | ชื่อท้องถิ่นของแอตทริบิวต์. |
| namespaceURI | const [String](../../../system/string/)\& | URI ของเนมสแพซของแอตทริบิวต์. |

### ค่าที่ส่งกลับ

แอตทริบิวต์ที่มีชื่อท้องถิ่นและ URI ของเนมสแพซตามที่ระบุ หากแอตทริบิวต์ไม่มีอยู่ เมธอดนี้จะส่งคืน **nullptr**.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlAttribute](../../xmlattribute/)
* คลาส [XmlAttributeCollection](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)