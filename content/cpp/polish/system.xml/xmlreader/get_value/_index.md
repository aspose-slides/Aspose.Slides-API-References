---
title: get_Value()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Po przesłonięciu w klasie pochodnej pobiera tekstową wartość bieżącego węzła.
type: docs
weight: 92
url: /pl/system.xml/xmlreader/get_value/
---
## XmlReader::get_Value() method


Po przesłonięciu w klasie pochodnej pobiera tekstową wartość bieżącego węzła.

```cpp
virtual String System::Xml::XmlReader::get_Value()=0
```


### Return Value

Zwracana wartość zależy od wartości [XmlReader::get_NodeType](../get_nodetype/) węzła.
## Remarks



Poniższa tabela wymienia typy węzłów, które posiadają wartość do zwrócenia. Wszystkie pozostałe typy węzłów zwracają [String::Empty](../../../system/string/empty/). 

| Node type | Value |
| --- | --- |
| `[Attribute](../../../system/attribute/)`| Wartość atrybutu. |
| `CDATA`| Zawartość sekcji CDATA. |
| `Comment`| Zawartość komentarza. |
| `DocumentType`| Podzbiór wewnętrzny. |
| `ProcessingInstruction`| Cała zawartość, z wyłączeniem celu. |
| `SignificantWhitespace`| Biała spacja pomiędzy znacznikami w modelu zawartości mieszanej. |
| `[Text](../../../system.text/)`| Zawartość węzła tekstowego. |
| `Whitespace`| Biała spacja pomiędzy znacznikami. |
| [XmlDeclaration](../../xmldeclaration/)| Zawartość deklaracji. |


## See Also

* Klasa [String](../../../system/string/)
* Klasa [XmlReader](../)
* Przestrzeń nazw [System::Xml](../../)
* Library [Aspose.Slides](../../../)