---
title: MoveToAttribute()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ย้ายไปยังแอตทริบิวต์ที่มีชื่อที่ระบุ
type: docs
weight: 508
url: /th/system.xml/xmltextreader/movetoattribute/
---
## XmlTextReader::MoveToAttribute(String) เมธอด


ย้ายไปยังแอตทริบิวต์ที่มีชื่อที่ระบุ

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String name) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อที่มีคุณสมบัติครบของแอตทริบิวต์ |

### ค่าที่ส่งคืน

**true** หากพบแอตทริบิวต์; มิฉะนั้น **false**. หาก **false** ตำแหน่งของตัวอ่านจะไม่เปลี่ยน

## XmlTextReader::MoveToAttribute(String, String) เมธอด


ย้ายไปยังแอตทริบิวต์ที่มีชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุ

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String localName, String namespaceURI) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| localName | [String](../../../system/string/) | ชื่อท้องถิ่นของแอตทริบิวต์ |
| namespaceURI | [String](../../../system/string/) | URI ของเนมสเปซของแอตทริบิวต์ |

### ค่าที่ส่งคืน

**true** หากพบแอตทริบิวต์; มิฉะนั้น **false**. หาก **false** ตำแหน่งของตัวอ่านจะไม่เปลี่ยน

## XmlTextReader::MoveToAttribute(int32_t) เมธอด


ย้ายไปยังแอตทริบิวต์ที่มีดัชนีที่ระบุ

```cpp
void System::Xml::XmlTextReader::MoveToAttribute(int32_t i) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| i | **int32_t** | ดัชนีของแอตทริบิวต์ |

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlTextReader](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)