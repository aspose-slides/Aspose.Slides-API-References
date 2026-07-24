---
title: WriteProcessingInstruction()
second_title: Aspose.Slides für C++ API-Referenz
description: "Schreibt eine Verarbeitungsanweisung mit einem Leerzeichen zwischen Name und Text wie folgt: <?name text?>."
type: docs
weight: 326
url: /de/system.xml/xmltextwriter/writeprocessinginstruction/
---
## XmlTextWriter::WriteProcessingInstruction(String, String) Methode

Schreibt eine Verarbeitungsanweisung mit einem Leerzeichen zwischen Name und Text wie folgt: **<?name text?>**.

```cpp
void System::Xml::XmlTextWriter::WriteProcessingInstruction(String name, String text) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | [String](../../../system/string/) | Name der Verarbeitungsanweisung. |
| text | [String](../../../system/string/) | [Text](../../../system.text/) zum Einfügen in die Verarbeitungsanweisung. |

## Anmerkungen

Diese Methode wird verwendet, um eine XML-Deklaration zu erstellen, nachdem [XmlTextWriter::WriteStartDocument](../writestartdocument/) bereits aufgerufen wurde.

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XmlTextWriter](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)