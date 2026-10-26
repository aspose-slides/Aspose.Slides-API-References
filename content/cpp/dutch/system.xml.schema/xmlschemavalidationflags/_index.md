---
title: XmlSchemaValidationFlags
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert schema-validatie-opties die worden gebruikt door de XmlSchemaValidator- en XmlReader-klassen.
type: docs
weight: 1054
url: /nl/system.xml.schema/xmlschemavalidationflags/
---
## XmlSchemaValidationFlags enum

Specificeert schema-validatie-opties die worden gebruikt door de [XmlSchemaValidator](../xmlschemavalidator/) en [XmlReader](../../system.xml/xmlreader/) klassen.

```cpp
enum class XmlSchemaValidationFlags
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| None | 0 | Verwerk geen identity constraints, inline schema's, schema-locatie-hints of rapporteer geen schema-validatiewaarschuwingen. |
| ProcessInlineSchema | 1 | Verwerk inline schema's die tijdens validatie worden aangetroffen. |
| ProcessSchemaLocation | 2 | Verwerk schema-locatie-hints (**xsi:schemaLocation**, **xsi:noNamespaceSchemaLocation**) die tijdens validatie worden aangetroffen. |
| ReportValidationWarnings | 4 | Rapporteer schema-validatiewaarschuwingen die tijdens validatie worden aangetroffen. |
| ProcessIdentityConstraints | 8 | Verwerk identity constraints (**xs:ID**, **xs:IDREF**, **xs:key**, **xs:keyref**, **xs:unique**) die tijdens validatie worden aangetroffen. |
| AllowXmlAttributes | 16 | Sta xml:* attributen toe, zelfs als ze niet in het schema zijn gedefinieerd. De attributen worden gevalideerd op basis van hun gegevenstype. |

## Zie ook

* Naamruimte [System::Xml::Schema](../)
* Bibliotheek [Aspose.Slides](../../)