---
title: get_Name()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Zwraca kwalifikowaną nazwę bieżącego węzła.
type: docs
weight: 14
url: /pl/system.xml/xmlnodereader/get_name/
---
## XmlNodeReader::get_Name() metoda

Zwraca kwalifikowaną nazwę bieżącego węzła.

```cpp
String System::Xml::XmlNodeReader::get_Name() override
```

### Wartość zwracana

Kwalifikowana nazwa bieżącego węzła. Na przykład, **Name** jest **bk:book** dla elementu **<bk:book>**.

## Uwagi

Zwracana nazwa zależy od wartości [XmlNodeReader::get_NodeType](../get_nodetype/) węzła. Następujące typy węzłów zwracają wymienione wartości. Wszystkie inne typy węzłów zwracają pusty ciąg.

| Typ węzła | Nazwa |
| --- | --- |
| [Attribute](../../../system/attribute/) | Nazwa atrybutu. |
| DocumentType | Nazwa typu dokumentu. |
| Element | Nazwa znacznika. |
| EntityReference | Nazwa odwoływanego podmiotu. |
| ProcessingInstruction | Cel instrukcji przetwarzania. |
| [XmlDeclaration](../../xmldeclaration/) | Literał ciągu `xml`. |

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlNodeReader](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)