---
title: get_Value()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Zwraca tekstową wartość bieżącego węzła.
type: docs
weight: 79
url: /pl/system.xml/xmltextreader/get_value/
---
## XmlTextReader::get_Value() metoda

Zwraca tekstową wartość bieżącego węzła.

```cpp
String System::Xml::XmlTextReader::get_Value() override
```

### Wartość zwracana

Zwracana wartość zależy od wartości [XmlTextReader::get_NodeType](../get_nodetype/) węzła.

## Uwagi

Poniższa tabela wymienia typy węzłów, które posiadają wartość do zwrócenia. Wszystkie pozostałe typy węzłów zwracają [String::Empty](../../../system/string/empty/).

| Typ węzła | Wartość |
| --- | --- |
| [Attribute](../../../system/attribute/)| Wartość atrybutu. |
| CDATA| Zawartość sekcji CDATA. |
| Comment| Zawartość komentarza. |
| DocumentType| Podzbiór wewnętrzny. |
| ProcessingInstruction| Cała zawartość, z wyłączeniem celu. |
| SignificantWhitespace| Białe znaki w zakresie `xml:space='preserve'`. |
| [Text](../../../system.text/)| Zawartość węzła tekstowego. |
| Whitespace| Białe znaki między znacznikami. |
| [XmlDeclaration](../../xmldeclaration/)| Zawartość deklaracji. |

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlTextReader](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)