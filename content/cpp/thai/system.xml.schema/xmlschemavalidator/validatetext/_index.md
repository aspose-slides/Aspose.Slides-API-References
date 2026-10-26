---
title: ValidateText()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: ตรวจสอบว่าข้อความสตริงที่ระบุได้รับอนุญาตในบริบทขององค์ประกอบปัจจุบันหรือไม่ และรวบรวมข้อความสำหรับการตรวจสอบหากองค์ประกอบปัจจุบันมีเนื้อหาง่าย
type: docs
weight: 183
url: /th/system.xml.schema/xmlschemavalidator/validatetext/
---
## XmlSchemaValidator::ValidateText(const String\&) เมธอด

ตรวจสอบว่าข้อความ **สตริง** ที่ระบุได้รับอนุญาตในบริบทขององค์ประกอบปัจจุบันหรือไม่ และรวบรวมข้อความสำหรับการตรวจสอบหากองค์ประกอบปัจจุบันมีเนื้อหาง่าย

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateText(const String &elementValue)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| elementValue | const [String](../../../system/string/)\& | ข้อความ **สตริง** เพื่อทำการตรวจสอบในบริบทขององค์ประกอบปัจจุบัน |

## XmlSchemaValidator::ValidateText(XmlValueGetter) เมธอด

ตรวจสอบว่าข้อความที่คืนมาจากอ็อบเจ็กต์ XmlValueGetter ที่ระบุได้รับอนุญาตในบริบทขององค์ประกอบปัจจุบันหรือไม่ และรวบรวมข้อความสำหรับการตรวจสอบหากองค์ประกอบปัจจุบันมีเนื้อหาง่าย

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateText(XmlValueGetter elementValue)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| elementValue | [XmlValueGetter](../../xmlvaluegetter/) | คอลแบ็ก XmlValueGetter ที่ใช้เพื่อส่งค่าข้อความในรูปแบบที่เข้ากันได้กับ XML [Schema](../../) Definition Language (XSD) type ของแอตทริบิวต์ |

## ดูเพิ่มเติม

* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* คลาส [String](../../../system/string/)
* คลาส [XmlSchemaValidator](../)
* เนมสเปซ [System::Xml::Schema](../../)
* ไลบรารี [Aspose.Slides](../../../)