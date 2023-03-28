---
title: get_ValidationFlags()
second_title: Aspose.Slides for C++ API Reference
description: "Returns a value indicating the schema validation settings. This setting applies to XmlReader objects that validate schemas (XmlReaderSettings::get_ValidationType value is ValidationType::Schema)."
type: docs
weight: 378
url: /cpp/system.xml/xmlreadersettings/get_validationflags/
---
## XmlReaderSettings::get_ValidationFlags() method


Returns a value indicating the schema validation settings. This setting applies to [XmlReader](../../xmlreader/) objects that validate schemas ([XmlReaderSettings::get_ValidationType](../get_validationtype/) value is [ValidationType::Schema](../../validationtype/)).

```cpp
Schema::XmlSchemaValidationFlags System::Xml::XmlReaderSettings::get_ValidationFlags()
```


### Return Value

A bitwise combination of enumeration values that specify validation options. XmlSchemaValidationFlags::ProcessIdentityConstraints and XmlSchemaValidationFlags::AllowXmlAttributes are enabled by default. XmlSchemaValidationFlags::ProcessInlineSchema, XmlSchemaValidationFlags::ProcessSchemaLocation and XmlSchemaValidationFlags::ReportValidationWarnings are disabled by default.

## See Also

* Enum [XmlSchemaValidationFlags](../../../system.xml.schema/xmlschemavalidationflags/)
* Class [XmlReaderSettings](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
