---
title: GetAttribute()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: คืนค่าของแอตทริบิวต์ที่มีชื่อที่ระบุ
type: docs
weight: 495
url: /th/system.xml/xmltextreader/getattribute/
---
## XmlTextReader::GetAttribute(String) เมธอด


คืนค่าของแอตทริบิวต์ที่มีชื่อที่ระบุ

```cpp
String System::Xml::XmlTextReader::GetAttribute(String name) override
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อที่มีคุณสมบัติเครบถ้วนของแอตทริบิวต์ |

### ค่าที่ส่งกลับ

ค่าของแอตทริบิวต์ที่ระบุ หากไม่พบแอตทริบิวต์ จะคืนค่า **nullptr**

## XmlTextReader::GetAttribute(String, String) เมธอด


คืนค่าของแอตทริบิวต์ที่มีชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุ

```cpp
String System::Xml::XmlTextReader::GetAttribute(String localName, String namespaceURI) override
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | ชื่อท้องถิ่นของแอตทริบิวต์ |
| namespaceURI | [String](../../../system/string/) | URI ของเนมสเปซของแอตทริบิวต์ |

### ค่าที่ส่งกลับ

ค่าของแอตทริบิวต์ที่ระบุ หากไม่พบแอตทริบิวต์ จะคืนค่า **nullptr** เมธอดนี้ไม่ทำการย้ายตัวอ่าน

## XmlTextReader::GetAttribute(int32_t) เมธอด


คืนค่าของแอตทริบิวต์ที่มีดัชนีที่ระบุ

```cpp
String System::Xml::XmlTextReader::GetAttribute(int32_t i) override
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| i | **int32_t** | ดัชนีของแอตทริบิวต์ ดัชนีเริ่มจากศูนย์ (แอตทริบิวต์แรกมีดัชนี 0) |

### ค่าที่ส่งกลับ

ค่าของแอตทริบิวต์ที่ระบุ

## ดูเพิ่มเติม

* Class [String](../../../system/string/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)