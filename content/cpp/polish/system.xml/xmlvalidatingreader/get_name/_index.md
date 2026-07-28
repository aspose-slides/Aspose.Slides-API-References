---
title: get_Name()
second_title: Aspose.Slides dla C++ Referencja API
description: Zwraca w pełni kwalifikowaną nazwę bieżącego węzła.
type: docs
weight: 14
url: /pl/system.xml/xmlvalidatingreader/get_name/
---
## XmlValidatingReader::get_Name() metoda

Zwraca w pełni kwalifikowaną nazwę bieżącego węzła.

```cpp
String System::Xml::XmlValidatingReader::get_Name() override
```

### Wartość zwracana

W pełni kwalifikowana nazwa bieżącego węzła. Na przykład, **Name** to **bk:book** dla elementu **<bk:book>**.

## Uwagi

Zwracana nazwa zależy od XmlValidatingReader::NodeType węzła. Następujące typy węzłów zwracają wymienione wartości. Wszystkie inne typy węzłów zwracają pusty łańcuch.

| Typ węzła | Nazwa |
| --- | --- |
| [Attribute](../../../system/attribute/)| Nazwa atrybutu. |
| DocumentType| Nazwa typu dokumentu. |
| Element| Nazwa znacznika. |
| EntityReference| Nazwa odwoływanej encji. |
| ProcessingInstruction| Cel instrukcji przetwarzania. |
| [XmlDeclaration](../../xmldeclaration/)| Literał ciągu znaków `xml`. |

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlValidatingReader](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)