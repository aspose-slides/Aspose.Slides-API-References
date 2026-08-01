---
title: get_ValidationFlags()
second_title: Aspose.Slides voor C++ API-referentie
description: "Retourneert een waarde die de instellingen voor schema-validatie aangeeft. Deze instelling is van toepassing op XmlReader-objecten die schema's valideren (XmlReaderSettings::get_ValidationType waarde is ValidationType::Schema)."
type: docs
weight: 378
url: /nl/system.xml/xmlreadersettings/get_validationflags/
---
## XmlReaderSettings::get_ValidationFlags() methode


Retourneert een waarde die de schema-validatie-instellingen aangeeft. Deze instelling is van toepassing op [XmlReader](../../xmlreader/) objecten die schema's valideren ([XmlReaderSettings::get_ValidationType](../get_validationtype/) waarde is [ValidationType::Schema](../../validationtype/)).

```cpp
Schema::XmlSchemaValidationFlags System::Xml::XmlReaderSettings::get_ValidationFlags()
```


### Retourwaarde

Een bitgewijze combinatie van enumeratiewaarden die validatieopties specificeren. XmlSchemaValidationFlags::ProcessIdentityConstraints en XmlSchemaValidationFlags::AllowXmlAttributes zijn standaard ingeschakeld. XmlSchemaValidationFlags::ProcessInlineSchema, XmlSchemaValidationFlags::ProcessSchemaLocation en XmlSchemaValidationFlags::ReportValidationWarnings zijn standaard uitgeschakeld.

## Zie ook

* Enum [XmlSchemaValidationFlags](../../../system.xml.schema/xmlschemavalidationflags/)
* Klasse [XmlReaderSettings](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)