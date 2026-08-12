---
title: WriteStartAttribute()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เขียนส่วนเริ่มต้นของแอตทริบิวต์โดยใช้ชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุ.
type: docs
weight: 144
url: /th/system.xml/xmlwriter/writestartattribute/
---
## XmlWriter::WriteStartAttribute(const String\&, const String\&) เมธอด

เขียนจุดเริ่มต้นของแอตทริบิวต์พร้อมชื่อท้องถิ่นและ URI ของเนมสเปซที่ระบุ.

```cpp
void System::Xml::XmlWriter::WriteStartAttribute(const String &localName, const String &ns)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | ชื่อท้องถิ่นของแอตทริบิวต์ |
| ns | const [String](../../../system/string/)\& | URI ของเนมสเปซของแอตทริบิวต์ |

## XmlWriter::WriteStartAttribute(const String\&, const String\&, const String\&) เมธอด

เมื่อทำการ overriding ในคลาสที่สืบทอด, จะเขียนจุดเริ่มต้นของแอตทริบิวต์พร้อมคำนำหน้า, ชื่อท้องถิ่น, และ URI ของเนมสเปซที่ระบุ.

```cpp
virtual void System::Xml::XmlWriter::WriteStartAttribute(const String &prefix, const String &localName, const String &ns)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | คำนำหน้าของเนมสเปซของแอตทริบิวต์ |
| localName | const [String](../../../system/string/)\& | ชื่อท้องถิ่นของแอตทริบิวต์ |
| ns | const [String](../../../system/string/)\& | URI ของเนมสเปซสำหรับแอตทริบิวต์ |

## XmlWriter::WriteStartAttribute(const String\&) เมธอด

เขียนจุดเริ่มต้นของแอตทริบิวต์พร้อมชื่อท้องถิ่นที่ระบุ.

```cpp
void System::Xml::XmlWriter::WriteStartAttribute(const String &localName)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | ชื่อท้องถิ่นของแอตทริบิวต์ |

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlWriter](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)