---
title: WriteProcessingInstruction()
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Gdy zostanie przesłonięta w klasie pochodnej, zapisuje instrukcję przetwarzania ze spacją pomiędzy nazwą a tekstem w następujący sposób: <?name text?>."
type: docs
weight: 196
url: /pl/system.xml/xmlwriter/writeprocessinginstruction/
---
## XmlWriter::WriteProcessingInstruction(String, String) metoda

Gdy zostanie przesłonięta w klasie pochodnej, zapisuje instrukcję przetwarzania ze spacją pomiędzy nazwą a tekstem w następujący sposób: **<?name text?>**.

```cpp
virtual void System::Xml::XmlWriter::WriteProcessingInstruction(String name, String text)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nazwa instrukcji przetwarzania. |
| text | [String](../../../system/string/) | Tekst do umieszczenia w instrukcji przetwarzania. |

## Uwagi

Ta metoda jest używana do utworzenia deklaracji XML po wywołaniu [XmlWriter::WriteStartDocument](../writestartdocument/).

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlWriter](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)