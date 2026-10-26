---
title: XmlSchemaValidationFlags
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die Optionen zur Schemaüberprüfung an, die von den Klassen XmlSchemaValidator und XmlReader verwendet werden.
type: docs
weight: 1054
url: /de/system.xml.schema/xmlschemavalidationflags/
---
## XmlSchemaValidationFlags Enum

Gibt die Optionen zur Schemaüberprüfung an, die von den Klassen [XmlSchemaValidator](../xmlschemavalidator/) und [XmlReader](../../system.xml/xmlreader/) verwendet werden.

```cpp
enum class XmlSchemaValidationFlags
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| None | 0 | Verarbeitet keine Identitätsbeschränkungen, Inline-Schemas, Schema-Standort-Hinweise oder meldet keine Schema-Validierungswarnungen. |
| ProcessInlineSchema | 1 | Verarbeitet während der Validierung gefundene Inline-Schemas. |
| ProcessSchemaLocation | 2 | Verarbeitet während der Validierung gefundene Schema-Standort-Hinweise (**xsi:schemaLocation**, **xsi:noNamespaceSchemaLocation**). |
| ReportValidationWarnings | 4 | Meldet während der Validierung gefundene Schema-Validierungswarnungen. |
| ProcessIdentityConstraints | 8 | Verarbeitet während der Validierung gefundene Identitätsbeschränkungen (**xs:ID**, **xs:IDREF**, **xs:key**, **xs:keyref**, **xs:unique**). |
| AllowXmlAttributes | 16 | Erlaubt xml:*-Attribute, selbst wenn sie im Schema nicht definiert sind. Die Attribute werden basierend auf ihrem Datentyp validiert. |

## Siehe auch

* Namespace [System::Xml::Schema](../)
* Bibliothek [Aspose.Slides](../../)