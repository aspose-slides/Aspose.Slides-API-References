---
title: XmlSchemaContentProcessing
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt Informationen zum Validierungsmodus von any- und anyAttribute-Elementersetzungen.
type: docs
weight: 976
url: /de/system.xml.schema/xmlschemacontentprocessing/
---
## XmlSchemaContentProcessing enum

Gibt Informationen zum Validierungsmodus von **any**- und **anyAttribute**-Elementersetzungen.

```cpp
enum class XmlSchemaContentProcessing
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| None | 0 | Dokumentelemente werden nicht validiert. |
| Skip | 1 | Dokumentelemente müssen wohlgeformtes XML enthalten und werden nicht vom Schema validiert. |
| Lax | 2 | Wenn das zugehörige Schema gefunden wird, werden die Dokumentelemente validiert. Andernfalls werden keine Fehler ausgelöst. |
| Strict | 3 | Der Schemaprozessor muss ein dem angegebenen Namensraum zugeordnetes Schema finden, um die Dokumentelemente zu validieren. |

## Siehe auch

* Namensraum [System::Xml::Schema](../)
* Bibliothek [Aspose.Slides](../../)