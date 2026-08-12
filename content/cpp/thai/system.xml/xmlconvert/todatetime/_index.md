---
title: ToDateTime()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แปลง String ให้เป็นค่าเทียบเท่า DateTime.
type: docs
weight: 417
url: /th/system.xml/xmlconvert/todatetime/
---
## XmlConvert::ToDateTime(const String\&) เมธอด

แปลง [String](../../../system/string/) เป็นค่าเทียบเท่า [DateTime](../../../system/datetime/).

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | สตริงที่ต้องแปลง. |

### ค่าที่ส่งกลับ

ค่าเทียบเท่า [DateTime](../../../system/datetime/) ของสตริง.

## XmlConvert::ToDateTime(const String\&, const String\&) เมธอด

แปลง [String](../../../system/string/) เป็นค่าเทียบเท่า [DateTime](../../../system/datetime/).

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const String &format)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | สตริงที่ต้องแปลง. |
| format | const [String](../../../system/string/)\& | โครงสร้างรูปแบบที่จะนำไปใช้กับ [DateTime](../../../system/datetime/) ที่แปลงแล้ว รูปแบบที่ถูกต้องรวมถึง "yyyy-MM-ddTHH:mm:sszzzzzz" และส่วนย่อยของมัน สตริงจะถูกตรวจสอบตามรูปแบบนี้. |

### ค่าที่ส่งกลับ

ค่าเทียบเท่า [DateTime](../../../system/datetime/) ของสตริง.

## XmlConvert::ToDateTime(const String\&, const ArrayPtr\<String\>\&) เมธอด

แปลง [String](../../../system/string/) เป็นค่าเทียบเท่า [DateTime](../../../system/datetime/).

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const ArrayPtr<String> &formats)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | สตริงที่ต้องแปลง. |
| formats | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | อาร์เรย์ที่บรรจุโครงสร้างรูปแบบที่จะนำไปใช้กับ [DateTime](../../../system/datetime/) ที่แปลงแล้ว รูปร่างที่ถูกต้องรวมถึง "yyyy-MM-ddTHH:mm:sszzzzzz" และส่วนย่อยของมัน. |

### ค่าที่ส่งกลับ

ค่าเทียบเท่า [DateTime](../../../system/datetime/) ของสตริง.

## XmlConvert::ToDateTime(const String\&, XmlDateTimeSerializationMode) เมธอด

แปลง [String](../../../system/string/) ให้เป็นค่าเทียบเท่า [DateTime](../../../system/datetime/) โดยใช้ XmlDateTimeSerializationMode ที่ระบุ.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, XmlDateTimeSerializationMode dateTimeOption)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | ค่า [String](../../../system/string/) ที่ต้องแปลง. |
| dateTimeOption | [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/) | หนึ่งในค่าของ enumeration ที่กำหนดว่าควรแปลงวันที่เป็นเวลาในท้องถิ่นหรือคงไว้เป็นเวลา Coordinated Universal Time (UTC) หากเป็นวันที่ UTC. |

### ค่าที่ส่งกลับ

ค่าเทียบเท่า [DateTime](../../../system/datetime/) ของ [String](../../../system/string/).

## ดูเพิ่มเติม

* Enum [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [DateTime](../../../system/datetime/)
* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)