---
title: get_LocalName()
second_title: Aspose.Slides for C++ – Dokumentacja API
description: Zwraca lokalną nazwę bieżącego węzła.
type: docs
weight: 27
url: /pl/system.xml/xmlnodereader/get_localname/
---
## XmlNodeReader::get_LocalName() metoda


Zwraca lokalną nazwę bieżącego węzła.

```cpp
String System::Xml::XmlNodeReader::get_LocalName() override
```


### Wartość zwracana

Nazwa bieżącego węzła z usuniętym prefiksem. Na przykład, **LocalName** to **book** dla elementu **<bk:book>**. Dla typów węzłów, które nie mają nazwy (takich jak **[Text](../../../system.text/)**, **Comment**, i tak dalej), ta metoda zwraca [String::Empty](../../../system/string/empty/).

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlNodeReader](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)