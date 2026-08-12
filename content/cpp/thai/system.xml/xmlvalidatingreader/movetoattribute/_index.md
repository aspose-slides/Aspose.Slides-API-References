---
title: MoveToAttribute()
second_title: Aspose.Slides สำหรับอ้างอิง API C++
description: ย้ายไปยังแอตทริบิวต์ที่มีชื่อที่ระบุ.
type: docs
weight: 456
url: /th/system.xml/xmlvalidatingreader/movetoattribute/
---
## XmlValidatingReader::MoveToAttribute(String) เมธอด


ย้ายไปยังแอตทริบิวต์ที่มีชื่อที่ระบุ.

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String name) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อที่สมบูรณ์ของแอตทริบิวต์. |

### ค่าที่ส่งคืน

**true** ถ้าแอตทริบิวต์ถูกพบ; มิฉะนั้น **false**. หาก **false**, ตำแหน่งของ reader ไม่เปลี่ยนแปลง.

## XmlValidatingReader::MoveToAttribute(String, String) เมธอด


ย้ายไปยังแอตทริบิวต์ที่มีชื่อท้องถิ่นและ Uniform Resource Identifier (URI) ของเนมสเปซที่ระบุ.

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String localName, String namespaceURI) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| localName | [String](../../../system/string/) | ชื่อท้องถิ่นของแอตทริบิวต์. |
| namespaceURI | [String](../../../system/string/) | URI ของเนมสเปซของแอตทริบิวต์. |

### ค่าที่ส่งคืน

**true** ถ้าแอตทริบิวต์ถูกพบ; มิฉะนั้น **false**. หาก **false**, ตำแหน่งของ reader ไม่เปลี่ยนแปลง.

## XmlValidatingReader::MoveToAttribute(int32_t) เมธอด


ย้ายไปยังแอตทริบิวต์ที่มีดัชนีที่ระบุ.

```cpp
void System::Xml::XmlValidatingReader::MoveToAttribute(int32_t i) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| i | **int32_t** | ดัชนีของแอตทริบิวต์. |

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlValidatingReader](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)