---
title: DtdProcessing
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die Optionen für die Verarbeitung von DTDs an. Die DtdProcessing-Enumeration wird von der XmlReaderSettings-Klasse verwendet.
type: docs
weight: 638
url: /de/system.xml/dtdprocessing/
---
## DtdProcessing-Enum

Gibt die Optionen für die Verarbeitung von DTDs an. Die DtdProcessing-Enumeration wird von der [XmlReaderSettings](../xmlreadersettings/)-Klasse verwendet.

```cpp
enum class DtdProcessing
```

### Werte

| Name | Value | Description |
| --- | --- | --- |
| Prohibit | 0 | Gibt an, dass beim Auftreten einer DTD eine XmlException mit einer Meldung ausgelöst wird, die besagt, dass DTDs verboten sind. Dies ist das Standardverhalten. |
| Ignore | 1 | Führt dazu, dass das DOCTYPE-Element ignoriert wird. Es findet keine DTD-Verarbeitung statt, und die DTD/DOCTYPE gehen bei der Ausgabe verloren. |
| Parse | 2 | Wird zum Parsen von DTDs verwendet. |

## Siehe auch

* Namensraum [System::Xml](../)
* Bibliothek [Aspose.Slides](../../)