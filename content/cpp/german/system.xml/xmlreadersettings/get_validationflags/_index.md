---
title: get_ValidationFlags()
second_title: Aspose.Slides für C++ API Referenz
description: "Gibt einen Wert zurück, der die Schema-Validierungseinstellungen angibt. Diese Einstellung gilt für XmlReader-Objekte, die Schemata validieren (XmlReaderSettings::get_ValidationType Wert ist ValidationType::Schema)."
type: docs
weight: 378
url: /de/system.xml/xmlreadersettings/get_validationflags/
---
## XmlReaderSettings::get_ValidationFlags() Methode

Gibt einen Wert zurück, der die Schema-Validierungseinstellungen angibt. Diese Einstellung gilt für [XmlReader](../../xmlreader/)-Objekte, die Schemata validieren ([XmlReaderSettings::get_ValidationType](../get_validationtype/)-Wert ist [ValidationType::Schema](../../validationtype/)).

```cpp
Schema::XmlSchemaValidationFlags System::Xml::XmlReaderSettings::get_ValidationFlags()
```

### Rückgabewert

Eine bitweise Kombination von Aufzählungswerten, die Validierungsoptionen angeben. XmlSchemaValidationFlags::ProcessIdentityConstraints und XmlSchemaValidationFlags::AllowXmlAttributes sind standardmäßig aktiviert. XmlSchemaValidationFlags::ProcessInlineSchema, XmlSchemaValidationFlags::ProcessSchemaLocation und XmlSchemaValidationFlags::ReportValidationWarnings sind standardmäßig deaktiviert.

## Siehe auch

* Enum [XmlSchemaValidationFlags](../../../system.xml.schema/xmlschemavalidationflags/)
* Klasse [XmlReaderSettings](../)
* Namensraum [System::Xml](../../)
* Library [Aspose.Slides](../../../)