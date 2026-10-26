---
title: WriteStartElement()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: เมื่อทำการ overriding ในคลาสที่สืบทอด, จะเขียนแท็กเริ่มต้นที่ระบุและเชื่อมโยงกับเนมสเปซที่กำหนด.
type: docs
weight: 92
url: /th/system.xml/xmlwriter/writestartelement/
---
## XmlWriter::WriteStartElement(const String\&, const String\&) เมธอด

เมื่อทำการ overriding ในคลาสที่สืบทอด, จะเขียนแท็กเริ่มต้นที่ระบุและเชื่อมโยงกับเนมสเปซที่กำหนด.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName, const String &ns)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | ชื่อท้องถิ่นขององค์ประกอบ. |
| ns | const [String](../../../system/string/)\& | URI ของเนมสเปซที่จะเชื่อมโยงกับองค์ประกอบ หากเนมสเปซนี้มีอยู่แล้วในสโคปและมีพรีฟิกซ์ที่เชื่อมโยง, ตัวเขียนจะเขียนพรีฟิกซ์นั้นโดยอัตโนมัติ. |

## XmlWriter::WriteStartElement(const String\&, const String\&, const String\&) เมธอด

เมื่อทำการ overriding ในคลาสที่สืบทอด, จะเขียนแท็กเริ่มต้นที่ระบุและเชื่อมโยงกับเนมสเปซและพรีฟิกซ์ที่กำหนด.

```cpp
virtual void System::Xml::XmlWriter::WriteStartElement(const String &prefix, const String &localName, const String &ns)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | พรีฟิกซ์ของเนมสเปซสำหรับองค์ประกอบ. |
| localName | const [String](../../../system/string/)\& | ชื่อท้องถิ่นขององค์ประกอบ. |
| ns | const [String](../../../system/string/)\& | URI ของเนมสเปซที่จะเชื่อมโยงกับองค์ประกอบ. |

## XmlWriter::WriteStartElement(const String\&) เมธอด

เมื่อทำการ overriding ในคลาสที่สืบทอด, จะเขียนแท็กเริ่มต้นด้วยชื่อท้องถิ่นที่ระบุ.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | ชื่อท้องถิ่นขององค์ประกอบ. |

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlWriter](../)
* เนมสเปซ [System::Xml](../../)
* Library [Aspose.Slides](../../../)