---
title: get_ValidationFlags()
second_title: Aspose.Slides for C++ API Referansı
description: "Şema doğrulama ayarlarını belirten bir değer döndürür. Bu ayar, şemaları doğrulayan XmlReader nesnelerine uygulanır (XmlReaderSettings::get_ValidationType değeri ValidationType::Schema'dir)."
type: docs
weight: 378
url: /tr/system.xml/xmlreadersettings/get_validationflags/
---
## XmlReaderSettings::get_ValidationFlags() metodu

Returns a value indicating the schema validation settings. This setting applies to [XmlReader](../../xmlreader/) objects that validate schemas ([XmlReaderSettings::get_ValidationType](../get_validationtype/) value is [ValidationType::Schema](../../validationtype/)).

```cpp
Schema::XmlSchemaValidationFlags System::Xml::XmlReaderSettings::get_ValidationFlags()
```

### Dönüş Değeri

A bitwise combination of enumeration values that specify validation options. XmlSchemaValidationFlags::ProcessIdentityConstraints and XmlSchemaValidationFlags::AllowXmlAttributes are enabled by default. XmlSchemaValidationFlags::ProcessInlineSchema, XmlSchemaValidationFlags::ProcessSchemaLocation and XmlSchemaValidationFlags::ReportValidationWarnings are disabled by default.

## Ayrıca Bakınız

* Enum [XmlSchemaValidationFlags](../../../system.xml.schema/xmlschemavalidationflags/)
* Sınıf [XmlReaderSettings](../)
* Ad Alanı [System::Xml](../../)
* Library [Aspose.Slides](../../../)