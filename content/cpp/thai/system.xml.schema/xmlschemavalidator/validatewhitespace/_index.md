---
title: ValidateWhitespace()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ตรวจสอบว่าขาวเว้นวรรคในสตริงที่ระบุได้รับอนุญาตในบริบทขององค์ประกอบปัจจุบันหรือไม่ และสะสมขาวเว้นวรรคสำหรับการตรวจสอบหากองค์ประกอบปัจจุบันมีเนื้อหาง่าย
type: docs
weight: 196
url: /th/system.xml.schema/xmlschemavalidator/validatewhitespace/
---
## XmlSchemaValidator::ValidateWhitespace(const String\&) เมธอด

ตรวจสอบว่าขาวเว้นวรรคใน **สตริง** ที่ระบุได้รับอนุญาตในบริบทขององค์ประกอบปัจจุบันหรือไม่ และสะสมขาวเว้นวรรคสำหรับการตรวจสอบหากองค์ประกอบปัจจุบันมีเนื้อหาง่าย

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateWhitespace(const String &elementValue)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| elementValue | const [String](../../../system/string/)\& | สตริงขาวเว้นวรรค **สตริง** เพื่อทำการตรวจสอบในบริบทขององค์ประกอบปัจจุบัน |

## XmlSchemaValidator::ValidateWhitespace(XmlValueGetter) เมธอด

ตรวจสอบว่าขาวเว้นวรรคที่ส่งกลับโดยวัตถุ XmlValueGetter ที่ระบุได้รับอนุญาตในบริบทขององค์ประกอบปัจจุบันหรือไม่ และสะสมขาวเว้นวรรคสำหรับการตรวจสอบหากองค์ประกอบปัจจุบันมีเนื้อหาง่าย

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateWhitespace(XmlValueGetter elementValue)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| elementValue | [XmlValueGetter](../../xmlvaluegetter/) | callback XmlValueGetter ที่ใช้เพื่อส่งค่าขาวเว้นวรรคในรูปแบบที่เข้ากันได้กับประเภท XML [Schema](../../) Definition Language (XSD) ของแอตทริบิวต์ |

## ดูเพิ่มเติม

* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* คลาส [String](../../../system/string/)
* คลาส [XmlSchemaValidator](../)
* เนมสเปซ [System::Xml::Schema](../../)
* ไลบรารี [Aspose.Slides](../../../)