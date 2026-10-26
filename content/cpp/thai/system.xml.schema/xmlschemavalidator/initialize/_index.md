---
title: Initialize()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เริ่มต้นสถานะของอ็อบเจ็กต์ XmlSchemaValidator.
type: docs
weight: 118
url: /th/system.xml.schema/xmlschemavalidator/initialize/
---
## XmlSchemaValidator::Initialize() เมธอด

เริ่มต้นสถานะของอ็อบเจ็กต์ [XmlSchemaValidator](../).

```cpp
void System::Xml::Schema::XmlSchemaValidator::Initialize()
```

## XmlSchemaValidator::Initialize(const SharedPtr\<XmlSchemaObject\>\&) เมธอด

เริ่มต้นสถานะของอ็อบเจ็กต์ [XmlSchemaValidator](../) โดยใช้ [XmlSchemaObject](../../xmlschemaobject/) ที่ระบุสำหรับการตรวจสอบบางส่วน.

```cpp
void System::Xml::Schema::XmlSchemaValidator::Initialize(const SharedPtr<XmlSchemaObject> &partialValidationType)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| partialValidationType | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaObject](../../xmlschemaobject/)\>\& | อ็อบเจ็กต์ [XmlSchemaElement](../../xmlschemaelement/), [XmlSchemaAttribute](../../xmlschemaattribute/) หรือ [XmlSchemaType](../../xmlschematype/) ที่ใช้ในการเริ่มต้นบริบทการตรวจสอบของอ็อบเจ็กต์ [XmlSchemaValidator](../) สำหรับการตรวจสอบบางส่วน. |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaValidator](../)
* Class [XmlSchemaObject](../../xmlschemaobject/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)