---
title: get_ValidationFlags()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "ส่งคืนค่าที่บ่งชี้การตั้งค่าการตรวจสอบ schema. การตั้งค่านี้ใช้กับอ็อบเจ็กต์ XmlReader ที่ทำการตรวจสอบ schema (ค่า XmlReaderSettings::get_ValidationType คือ ValidationType::Schema)."
type: docs
weight: 378
url: /th/system.xml/xmlreadersettings/get_validationflags/
---
## XmlReaderSettings::get_ValidationFlags() เมธอด

ส่งคืนค่าที่บ่งชี้การตั้งค่าการตรวจสอบ schema. การตั้งค่านี้ใช้กับอ็อบเจกต์ [XmlReader](../../xmlreader/) ที่ทำการตรวจสอบ schema (ค่าของ [XmlReaderSettings::get_ValidationType](../get_validationtype/) คือ [ValidationType::Schema](../../validationtype/)).

```cpp
Schema::XmlSchemaValidationFlags System::Xml::XmlReaderSettings::get_ValidationFlags()
```

### ค่าที่ส่งคืน

การผสมแบบบิตของค่าการนับที่ระบุตัวเลือกการตรวจสอบ. XmlSchemaValidationFlags::ProcessIdentityConstraints และ XmlSchemaValidationFlags::AllowXmlAttributes จะถูกเปิดใช้งานโดยค่าเริ่มต้น. XmlSchemaValidationFlags::ProcessInlineSchema, XmlSchemaValidationFlags::ProcessSchemaLocation และ XmlSchemaValidationFlags::ReportValidationWarnings จะถูกปิดใช้งานโดยค่าเริ่มต้น.

## ดูเพิ่มเติม

* Enum [XmlSchemaValidationFlags](../../../system.xml.schema/xmlschemavalidationflags/)
* คลาส [XmlReaderSettings](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)