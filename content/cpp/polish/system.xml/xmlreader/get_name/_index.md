---
title: get_Name()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Gdy zostanie przesłonięta w klasie pochodnej, zwraca w pełni kwalifikowaną nazwę bieżącego węzła.
type: docs
weight: 27
url: /pl/system.xml/xmlreader/get_name/
---
## XmlReader::get_Name() metoda


Gdy zostanie przesłonięta w klasie pochodnej, zwraca w pełni kwalifikowaną nazwę bieżącego węzła.

```cpp
virtual String System::Xml::XmlReader::get_Name()
```


### Wartość zwracana

W pełni kwalifikowana nazwa bieżącego węzła. Na przykład, **Name** to **bk:book** dla elementu **<bk:book>**.

## Uwagi



Zwracana nazwa zależy od wartości [XmlReader::get_NodeType](../get_nodetype/) węzła. Następujące typy węzłów zwracają wskazane wartości. Wszystkie pozostałe typy węzłów zwracają pusty ciąg. 

| Typ węzła | Nazwa |
| --- | --- |
| `[Attribute](../../../system/attribute/)`| Nazwa atrybutu. |
| `DocumentType`| Nazwa typu dokumentu. |
| `Element`| Nazwa znacznika. |
| `EntityReference`| Nazwa odwoływanego podmiotu. |
| `ProcessingInstruction`| Cel instrukcji przetwarzania. |
| [XmlDeclaration](../../xmldeclaration/)| Literalny ciąg znaków `xml`. |


## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlReader](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)