---
title: get_LocalName()
second_title: Biblioteka referencyjna API Aspose.Slides dla C++
description: Zwraca lokalną nazwę bieżącego węzła.
type: docs
weight: 27
url: /pl/system.xml/xmlvalidatingreader/get_localname/
---
## XmlValidatingReader::get_LocalName() metoda

Zwraca lokalną nazwę bieżącego węzła.

```cpp
String System::Xml::XmlValidatingReader::get_LocalName() override
```

### Wartość zwracana

Nazwa bieżącego węzła po usunięciu prefiksu. Na przykład, **LocalName** to **book** dla elementu **<bk:book>**. Dla typów węzłów, które nie mają nazwy (takich jak **[Text](../../../system.text/)**, **Comment**, i tak dalej), ta metoda zwraca [String::Empty](../../../system/string/empty/).

## Zobacz również

* Klasa [String](../../../system/string/)
* Klasa [XmlValidatingReader](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)