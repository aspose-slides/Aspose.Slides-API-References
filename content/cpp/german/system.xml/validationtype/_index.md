---
title: ValidationType
second_title: Aspose.Slides für C++ API Referenz
description: Gibt den Typ der durchzuführenden Validierung an.
type: docs
weight: 729
url: /de/system.xml/validationtype/
---
## ValidationType enum

Gibt den Typ der durchzuführenden Validierung an.

```cpp
enum class ValidationType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | Es wird keine Validierung durchgeführt und es werden keine Validierungsfehler ausgelöst. Diese Einstellung erzeugt einen XML-1.0-konformen nicht-validierenden Parser. |
| Auto | 1 | Validiert, wenn DTD- oder Schema-Informationen gefunden werden. |
| DTD | 2 | Validiert gemäß der DTD. |
| XDR | 3 | Validiert gemäß XML-Data Reduced (XDR)-Schemata, einschließlich eingebetteter XDR-Schemata. XDR-Schemata werden anhand des Namensraumpräfixes **x-schema** oder des [XmlValidatingReader::get_Schemas](../xmlvalidatingreader/get_schemas/)-Werts erkannt. |
| Schema | 4 | Validiert gemäß XML [Schema](../../system.xml.schema/) Definition Language (XSD)-Schemata, einschließlich eingebetteter XML-Schemata. XML-Schemata werden mit Namensraum-URIs entweder über das Attribut **schemaLocation** oder die bereitgestellten **Schemas** verknüpft. |

## Siehe auch

* Namensraum [System::Xml](../)
* Bibliothek [Aspose.Slides](../../)