---
title: get_LocalName()
second_title: Aspose.Slides - referencja API C++
description: Zwraca lokalną nazwę bieżącego węzła.
type: docs
weight: 27
url: /pl/system.xml/xmltextreader/get_localname/
---
## XmlTextReader::get_LocalName() metoda

Zwraca lokalną nazwę bieżącego węzła.

```cpp
String System::Xml::XmlTextReader::get_LocalName() override
```

### Wartość zwracana

Nazwa bieżącego węzła z usuniętym prefiksem. Na przykład, **LocalName** jest **book** dla elementu **<bk:book>**. Dla typów węzłów, które nie mają nazwy (takich jak **[Text](../../../system.text/)**, **Comment**, i tak dalej), ta metoda zwraca [String::Empty](../../../system/string/empty/).

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlTextReader](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)