---
title: GetAttribute()
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: "เมื่อทำการ override ในคลาสที่สืบทอด จะได้ค่าของแอตทริบิวต์ที่มีค่า XmlReader::get_Name ที่ระบุ"
type: docs
weight: 599
url: /th/system.xml/xmlreader/getattribute/
---
## XmlReader::GetAttribute(String) method

เมื่อทำการ override ในคลาสที่สืบทอด จะได้ค่าของ attribute ที่มีค่า [XmlReader::get_Name](../get_name/) ที่ระบุ

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name)=0
```

### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อที่ประกอบเต็มของ attribute |

### Return Value

ค่าของ attribute ที่ระบุ หากไม่พบ attribute หรือค่ามีค่า [String::Empty](../../../system/string/empty/) จะคืนค่า **nullptr**

## XmlReader::GetAttribute(String, String) method

เมื่อทำการ override ในคลาสที่สืบทอด จะได้ค่าของ attribute ที่มีค่า [XmlReader::get_LocalName](../get_localname/) และ [XmlReader::get_NamespaceURI](../get_namespaceuri/) ที่ระบุ

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name, String namespaceURI)=0
```

### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อท้องถิ่นของ attribute |
| namespaceURI | [String](../../../system/string/) | URI ของเนมสเปซของ attribute |

### Return Value

ค่าของ attribute ที่ระบุ หากไม่พบ attribute หรือค่ามีค่า [String::Empty](../../../system/string/empty/) จะคืนค่า **nullptr** วิธีนี้จะไม่ย้ายตัวอ่าน

## XmlReader::GetAttribute(int32_t) method

เมื่อทำการ override ในคลาสที่สืบทอด จะได้ค่าของ attribute ที่มีดัชนีที่ระบุ

```cpp
virtual String System::Xml::XmlReader::GetAttribute(int32_t i)=0
```

### Arguments

| พารามิ터 | ชนิด | คำอธิบาย |
| --- | --- | --- |
| i | **int32_t** | ดัชนีของ attribute ดัชนีเริ่มจากศูนย์ (attribute แรกมีดัชนี 0) |

### Return Value

ค่ของ attribute ที่ระบุ วิธีนี้จะไม่ย้ายตัวอ่าน

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlReader](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)