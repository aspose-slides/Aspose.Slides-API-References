---
title: get_Value()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Zwraca tekstową wartość bieżącego węzła.
type: docs
weight: 79
url: /pl/system.xml/xmlnodereader/get_value/
---
## XmlNodeReader::get_Value() metoda

Zwraca tekstową wartość bieżącego węzła.

```cpp
String System::Xml::XmlNodeReader::get_Value() override
```

### Wartość zwracana

Wartość zwracana zależy od [XmlNodeReader::get_NodeType](../get_nodetype/) węzła.

## Uwagi

Poniższa tabela wymienia typy węzłów, które mają wartość do zwrócenia. Wszystkie inne typy węzłów zwracają [String::Empty](../../../system/string/empty/).

| Typ węzła | Wartość |
| --- | --- |
| [Attribute](../../../system/attribute/)| Wartość atrybutu. |
| CDATA| Zawartość sekcji CDATA. |
| Comment| Zawartość komentarza. |
| DocumentType| Podzbiór wewnętrzny. |
| ProcessingInstruction| Cała zawartość, z wyłączeniem docelowego elementu. |
| SignificantWhitespace| Biała spacja między znacznikami w modelu zawartości mieszanej. |
| [Text](../../../system.text/)| Zawartość węzła tekstowego. |
| Whitespace| Biała spacja między znacznikami. |
| [XmlDeclaration](../../xmldeclaration/)| Zawartość deklaracji. |

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlNodeReader](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)