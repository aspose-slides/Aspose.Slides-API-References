---
title: get_ValidationFlags()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: "تُرجع قيمة تشير إلى إعدادات التحقق من المخطط. ينطبق هذا الإعداد على كائنات XmlReader التي تتحقق من المخططات (قيمة XmlReaderSettings::get_ValidationType هي ValidationType::Schema)."
type: docs
weight: 378
url: /ar/system.xml/xmlreadersettings/get_validationflags/
---
## XmlReaderSettings::get_ValidationFlags() طريقة

تُرجع قيمة تشير إلى إعدادات التحقق من المخطط. ينطبق هذا الإعداد على كائنات [XmlReader](../../xmlreader/) التي تتحقق من المخططات (القيمة [XmlReaderSettings::get_ValidationType](../get_validationtype/) هي [ValidationType::Schema](../../validationtype/)).

```cpp
Schema::XmlSchemaValidationFlags System::Xml::XmlReaderSettings::get_ValidationFlags()
```

### قيمة الإرجاع

دمج بتّي من قيم التعداد التي تحدد خيارات التحقق. XmlSchemaValidationFlags::ProcessIdentityConstraints و XmlSchemaValidationFlags::AllowXmlAttributes مفعّلان بشكل افتراضي. XmlSchemaValidationFlags::ProcessInlineSchema و XmlSchemaValidationFlags::ProcessSchemaLocation و XmlSchemaValidationFlags::ReportValidationWarnings موقّفان بشكل افتراضي.

## انظر أيضًا

* التعداد [XmlSchemaValidationFlags](../../../system.xml.schema/xmlschemavalidationflags/)
* الفئة [XmlReaderSettings](../)
* مساحة الاسم [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)