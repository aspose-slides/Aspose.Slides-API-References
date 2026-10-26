---
title: get_Value()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Zwraca tekstową wartość bieżącego węzła.
type: docs
weight: 79
url: /pl/system.xml/xmlvalidatingreader/get_value/
---
## XmlValidatingReader::get_Value() metoda


Zwraca tekstową wartość bieżącego węzła.

```cpp
String System::Xml::XmlValidatingReader::get_Value() override
```


### Wartość zwracana

Zwracana wartość zależy od XmlValidatingReader::NodeType węzła.
## Uwagi



Poniższa tabela wymienia typy węzłów, które mają wartość do zwrócenia. Wszystkie inne typy węzłów zwracają [String::Empty](../../../system/string/empty/). 

| Typ węzła | Wartość |
| --- | --- |
| [Attribute](../../../system/attribute/)| Wartość atrybutu. |
| CDATA| Zawartość sekcji CDATA. |
| Comment| Zawartość komentarza. |
| DocumentType| Podzbiór wewnętrzny. |
| ProcessingInstruction| Cała zawartość, z wyłączeniem celu. |
| SignificantWhitespace| Biała przestrzeń pomiędzy znacznikami w modelu mieszanej zawartości. |
| [Text](../../../system.text/)| Zawartość węzła tekstowego. |
| Whitespace| Biała przestrzeń pomiędzy znacznikami. |
| [XmlDeclaration](../../xmldeclaration/)| Zawartość deklaracji. |


## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlValidatingReader](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)