---
title: MoveToAttribute()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "เมื่อถูกเขียนทับในคลาสที่สืบทอด จะย้ายไปยังแอตทริบิวต์ที่มีค่า XmlReader::get_Name ที่ระบุ"
type: docs
weight: 625
url: /th/system.xml/xmlreader/movetoattribute/
---
## XmlReader::MoveToAttribute(String) เมธอด

When overridden in a derived class, moves to the attribute with the specified [XmlReader::get_Name](../get_name/) value.

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อที่สมบูรณ์ของแอตทริบิวต์. |

### ค่าที่คืน

**true** หากพบแอตทริบิวต์; ถ้าไม่, **false**. หาก **false**, ตำแหน่งของรีดเดอร์จะไม่เปลี่ยนแปลง.

## XmlReader::MoveToAttribute(String, String) เมธอด

When overridden in a derived class, moves to the attribute with the specified [XmlReader::get_LocalName](../get_localname/) and [XmlReader::get_NamespaceURI](../get_namespaceuri/) values.

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name, String ns)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | [String](../../../system/string/) | ชื่อท้องถิ่นของแอตทริบิวต์. |
| ns | [String](../../../system/string/) | URI ของเนมสเปซของแอตทริบิวต์. |

### ค่าที่คืน

**true** หากพบแอตทริบิวต์; ถ้าไม่, **false**. หาก **false**, ตำแหน่งของรีดเดอร์จะไม่เปลี่ยนแปลง.

## XmlReader::MoveToAttribute(int32_t) เมธอด

When overridden in a derived class, moves to the attribute with the specified index.

```cpp
virtual void System::Xml::XmlReader::MoveToAttribute(int32_t i)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| i | **int32_t** | ดัชนีของแอตทริบิวต์. |

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlReader](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)