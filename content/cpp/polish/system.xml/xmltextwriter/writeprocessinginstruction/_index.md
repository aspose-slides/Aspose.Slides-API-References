---
title: WriteProcessingInstruction()
second_title: Aspose.Slides dla C++ API Reference
description: "Zapisuje instrukcję przetwarzania z odstępem między nazwą a tekstem w następujący sposób: <?name text?>."
type: docs
weight: 326
url: /pl/system.xml/xmltextwriter/writeprocessinginstruction/
---
## XmlTextWriter::WriteProcessingInstruction(String, String) metoda

Writes out a processing instruction with a space between the name and text as follows: **<?name text?>**.

```cpp
void System::Xml::XmlTextWriter::WriteProcessingInstruction(String name, String text) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nazwa instrukcji przetwarzania. |
| text | [String](../../../system/string/) | [Text](../../../system.text/) do umieszczenia w instrukcji przetwarzania. |

## Uwagi

This method is being used to create an XML declaration after [XmlTextWriter::WriteStartDocument](../writestartdocument/) has already been called.

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlTextWriter](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)