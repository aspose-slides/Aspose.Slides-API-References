---
title: GetAttribute()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: ส่งคืนค่าของแอตทริบิวต์ที่มีชื่อที่ระบุ
type: docs
weight: 443
url: /th/system.xml/xmlvalidatingreader/getattribute/
---
## XmlValidatingReader::GetAttribute(String) เมธอด

ส่งคืนค่าของแอตทริบิวต์ที่มีชื่อที่ระบุ

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(String name) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อเต็มของแอตทริบิวต์ |

### ค่าที่คืนกลับ

ค่ของแอตทริบิวต์ที่ระบุ หากไม่พบแอตทริบิวต์ จะคืนค่า **nullptr**

## XmlValidatingReader::GetAttribute(String, String) เมธอด

ส่งคืนค่าของแอตทริบิวต์ที่มีชื่อท้องถิ่นและ Uniform Resource Identifier (URI) ของเนมสเปซที่ระบุ

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(String localName, String namespaceURI) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| localName | [String](../../../system/string/) | ชื่อท้องถิ่นของแอตทริบิวต์ |
| namespaceURI | [String](../../../system/string/) | URI ของเนมสเปซของแอตทริบิวต์ |

### ค่าที่คืนกลับ

ค่ของแอตทริบิวต์ที่ระบุ หากไม่พบแอตทริบิวต์ จะคืนค่า **nullptr** เมธอดนี้ไม่ได้ย้ายตัวอ่าน

## XmlValidatingReader::GetAttribute(int32_t) เมธอด

ส่งคืนค่ของแอตทริบิวต์ที่มีดัชนีที่ระบุ

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(int32_t i) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| i | **int32_t** | ดัชนีของแอตทริบิวต์ ดัชนีเริ่มจากศูนย์ (แอตทริบิวต์แรกมีดัชนี 0.) |

### ค่าที่คืนกลับ

ค่ของแอตทริบิวต์ที่ระบุ

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlValidatingReader](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)