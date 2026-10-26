---
title: WriteProcessingInstruction()
second_title: Aspose.Slides för C++ API-referens
description: "Skriver ut en bearbetningsinstruktion med ett mellanslag mellan namn och text på följande sätt: <?name text?>."
type: docs
weight: 326
url: /sv/system.xml/xmltextwriter/writeprocessinginstruction/
---
## XmlTextWriter::WriteProcessingInstruction(String, String) metod

Skriver ut en bearbetningsinstruktion med ett mellanslag mellan namn och text på följande sätt: **<?name text?>**.

```cpp
void System::Xml::XmlTextWriter::WriteProcessingInstruction(String name, String text) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | [String](../../../system/string/) | Namnet på bearbetningsinstruktionen. |
| text | [String](../../../system/string/) | [Text](../../../system.text/) att inkludera i bearbetningsinstruktionen. |

## Anmärkningar

Denna metod används för att skapa en XML-deklaration efter att [XmlTextWriter::WriteStartDocument](../writestartdocument/) redan har anropats. 

## Se även

* Klass [String](../../../system/string/)
* Klass [XmlTextWriter](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)