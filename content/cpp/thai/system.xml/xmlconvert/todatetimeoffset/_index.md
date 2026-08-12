---
title: ToDateTimeOffset()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แปลง String ที่ได้รับให้เป็นค่าเทียบเท่า DateTimeOffset.
type: docs
weight: 430
url: /th/system.xml/xmlconvert/todatetimeoffset/
---
## XmlConvert::ToDateTimeOffset(const String\&) เมธอด

แปลง [String](../../../system/string/) ที่ได้รับให้เป็นค่าเทียบเท่าของ [DateTimeOffset](../../../system/datetimeoffset/).

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | สตริงที่ต้องการแปลง สตริงต้องสอดคล้องกับส่วนย่อยของข้อแนะนำของ W3C สำหรับประเภท XML dateTime สำหรับข้อมูลเพิ่มเติม โปรดดูส่วน [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) ของสเปค XML [Schema](../../../system.xml.schema/) |

### ค่าที่ส่งกลับ

ค่าเทียบเท่าของ [DateTimeOffset](../../../system/datetimeoffset/) ที่ได้จากสตริงที่ส่งเข้า

## XmlConvert::ToDateTimeOffset(const String\&, const String\&) เมธอด

แปลง [String](../../../system/string/) ที่ได้รับให้เป็นค่าเทียบเท่าของ [DateTimeOffset](../../../system/datetimeoffset/).

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const String &format)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | สตริงที่ต้องการแปลง |
| format | const [String](../../../system/string/)\& | ฟอร์แมตที่ใช้ในการแปลง **s** ฟอร์แมตนี้อาจเป็นส่วนย่อยใด ๆ ของข้อแนะนำของ W3C สำหรับประเภท XML dateTime สำหรับข้อมูลเพิ่มเติม โปรดดูส่วน [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) ของสเปค XML [Schema](../../../system.xml.schema/) สตริง **s** จะถูกตรวจสอบตามฟอร์แมตนี้ |

### ค่าที่ส่งกลับ

ค่าเทียบเท่าของ [DateTimeOffset](../../../system/datetimeoffset/) ที่ได้จากสตริงที่ส่งเข้า

## XmlConvert::ToDateTimeOffset(const String\&, const ArrayPtr\<String\>\&) เมธอด

แปลง [String](../../../system/string/) ที่ได้รับให้เป็นค่าเทียบเท่าของ [DateTimeOffset](../../../system/datetimeoffset/).

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const ArrayPtr<String> &formats)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | สตริงที่ต้องการแปลง |
| formats | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | อาเรย์ของฟอร์แมตที่สามารถใช้แปลง **s** ฟอร์แมตแต่ละรายการใน **formats** อาจเป็นส่วนย่อยใด ๆ ของข้อแนะนำของ W3C สำหรับประเภท XML dateTime สำหรับข้อมูลเพิ่มเติม โปรดดูส่วน [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) ของสเปค XML [Schema](../../../system.xml.schema/) สตริง **s** จะถูกตรวจสอบกับหนึ่งในฟอร์แมตเหล่านี้ |

### ค่าที่ส่งกลับ

ค่าเทียบเท่าของ [DateTimeOffset](../../../system/datetimeoffset/) ที่ได้จากสตริงที่ส่งเข้า

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [DateTimeOffset](../../../system/datetimeoffset/)
* คลาส [String](../../../system/string/)
* คลาส [XmlConvert](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)