---
title: XmlSchemaValidationFlags
second_title: Aspose.Slides för C++ API-referens
description: Anger schema-valideringsalternativ som används av XmlSchemaValidator- och XmlReader-klasserna.
type: docs
weight: 1054
url: /sv/system.xml.schema/xmlschemavalidationflags/
---
## XmlSchemaValidationFlags enum

Anger schema-valideringsalternativ som används av [XmlSchemaValidator](../xmlschemavalidator/) och [XmlReader](../../system.xml/xmlreader/) klasserna.

```cpp
enum class XmlSchemaValidationFlags
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| None | 0 | Bearbeta inte identitetsbegränsningar, inbäddade scheman, schemalägeshintar eller rapportera schema-valideringsvarningar. |
| ProcessInlineSchema | 1 | Bearbeta inbäddade scheman som påträffas under validering. |
| ProcessSchemaLocation | 2 | Bearbeta schemalägeshintar (**xsi:schemaLocation**, **xsi:noNamespaceSchemaLocation**) som påträffas under validering. |
| ReportValidationWarnings | 4 | Rapportera schema-valideringsvarningar som påträffas under validering. |
| ProcessIdentityConstraints | 8 | Bearbeta identitetsbegränsningar (**xs:ID**, **xs:IDREF**, **xs:key**, **xs:keyref**, **xs:unique**) som påträffas under validering. |
| AllowXmlAttributes | 16 | Tillåt xml:* attribut även om de inte är definierade i schemat. Attributen kommer att valideras baserat på deras datatyp. |

## Se även

* Namnrymd [System::Xml::Schema](../)
* Bibliotek [Aspose.Slides](../../)