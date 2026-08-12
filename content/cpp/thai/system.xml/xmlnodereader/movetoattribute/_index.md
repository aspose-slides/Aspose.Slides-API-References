---
title: MoveToAttribute()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ย้ายไปยังแอตทริบิวต์ที่มีชื่อที่ระบุ
type: docs
weight: 300
url: /th/system.xml/xmlnodereader/movetoattribute/
---
## XmlNodeReader::MoveToAttribute(String) เมธอด


ย้ายไปยังแอตทริบิวต์ที่มีชื่อที่ระบุ

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อแบบเต็มของแอตทริบิวต์ |

### ค่าที่ส่งกลับ

**true** ถ้าเจอแอตทริบิวต์; มิฉะนั้น **false**. หาก **false**, ตำแหน่งของรีดเดอร์จะไม่เปลี่ยนแปลง

## XmlNodeReader::MoveToAttribute(String, String) เมธอด


ย้ายไปยังแอตทริบิวต์ที่มีชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุ

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name, String namespaceURI) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อท้องถิงของแอตทริบิวต์ |
| namespaceURI | [String](../../../system/string/) | URI ของเนมสเปซของแอตทริบิวต์ |

### ค่าที่ส่งกลับ

**true** ถ้าเจอแอตทริบิวต์; มิฉะนั้น **false**. หาก **false**, ตำแหน่งของรีดเดอร์จะไม่เปลี่ยนแปลง

## XmlNodeReader::MoveToAttribute(int32_t) เมธอด


ย้ายไปยังแอตทริบิวต์ที่มีดัชนีที่ระบุ

```cpp
void System::Xml::XmlNodeReader::MoveToAttribute(int32_t attributeIndex) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| attributeIndex | **int32_t** | ดัชนีของแอตทริบิวต์ |

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlNodeReader](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)