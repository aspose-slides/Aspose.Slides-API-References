---
title: get_LocalName()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Gdy zostanie przesłonięta w klasie pochodnej, zwraca lokalną nazwę bieżącego węzła.
type: docs
weight: 40
url: /pl/system.xml/xmlreader/get_localname/
---
## XmlReader::get_LocalName() metoda


Gdy zostanie przesłonięta w klasie pochodnej, zwraca lokalną nazwę bieżącego węzła.

```cpp
virtual String System::Xml::XmlReader::get_LocalName()=0
```


### Wartość zwracana

Nazwa bieżącego węzła z usuniętym prefiksem. Na przykład, **LocalName** to **book** dla elementu **<bk:book>**. Dla typów węzłów, które nie mają nazwy (takich jak **[Text](../../../system.text/)**, **Comment** i tak dalej), ta metoda zwraca [String::Empty](../../../system/string/empty/).

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlReader](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)