---
title: XmlSeverityType
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt die Schwere des Validierungsereignisses dar.
type: docs
weight: 1080
url: /de/system.xml.schema/xmlseveritytype/
---
## XmlSeverityType enum

Stellt die Schwere des Validierungsereignisses dar.

```cpp
enum class XmlSeverityType
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Error | 0 | Zeigt an, dass ein Validierungsfehler beim Validieren des Instanzdokuments aufgetreten ist. Dies gilt für Dokumenttypdefinitionen (DTDs) und XML [Schema](../) Definition Language (XSD) Schemas. Die World Wide [Web](../../system.web/) Consortium (W3C) Gültigkeitsbedingungen werden als Fehler betrachtet. Wenn kein Validierungsereignis-Handler erstellt wurde, lösen Fehler eine Ausnahme aus. |
| Warning | 1 | Zeigt an, dass ein Validierungsereignis aufgetreten ist, das kein Fehler ist. Eine Warnung wird typischerweise ausgegeben, wenn kein DTD vorhanden ist oder XML [Schema](../) zum Validieren eines bestimmten Elements oder Attributs fehlt. Im Gegensatz zu Fehlern werfen Warnungen keine Ausnahme, wenn kein Validierungsereignis-Handler vorhanden ist. |

## Siehe auch

* Namensraum [System::Xml::Schema](../)
* Bibliothek [Aspose.Slides](../../)