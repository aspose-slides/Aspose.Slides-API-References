---
title: get_ValidationFlags()
second_title: Aspose.Slides för C++ API-referens
description: "Returnerar ett värde som indikerar schemavalideringsinställningarna. Denna inställning gäller för XmlReader-objekt som validerar scheman (XmlReaderSettings::get_ValidationType-värdet är ValidationType::Schema)."
type: docs
weight: 378
url: /sv/system.xml/xmlreadersettings/get_validationflags/
---
## XmlReaderSettings::get_ValidationFlags() metod

Returnerar ett värde som indikerar schemavalideringsinställningarna. Denna inställning gäller för [XmlReader](../../xmlreader/)-objekt som validerar scheman ([XmlReaderSettings::get_ValidationType](../get_validationtype/)-värdet är [ValidationType::Schema](../../validationtype/)).

```cpp
Schema::XmlSchemaValidationFlags System::Xml::XmlReaderSettings::get_ValidationFlags()
```

### Returvärde

En bitvis kombination av uppräkningsvärden som specificerar valideringsalternativ. XmlSchemaValidationFlags::ProcessIdentityConstraints och XmlSchemaValidationFlags::AllowXmlAttributes är aktiverade som standard. XmlSchemaValidationFlags::ProcessInlineSchema, XmlSchemaValidationFlags::ProcessSchemaLocation och XmlSchemaValidationFlags::ReportValidationWarnings är inaktiverade som standard.

## Se också

* Enum [XmlSchemaValidationFlags](../../../system.xml.schema/xmlschemavalidationflags/)
* Klass [XmlReaderSettings](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)