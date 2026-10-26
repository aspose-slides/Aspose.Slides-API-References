---
title: ReadAttributeValue()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Gdy zostanie nadpisana w klasie pochodnej, analizuje wartość atrybutu na jeden lub więcej węzłów Text, EntityReference lub EndEntity.
type: docs
weight: 677
url: /pl/system.xml/xmlreader/readattributevalue/
---
## XmlReader::ReadAttributeValue() metoda

Gdy zostanie nadpisana w klasie pochodnej, analizuje wartość atrybutu na jeden lub więcej węzłów **[Text](../../../system.text/)**, **EntityReference** lub **EndEntity**.

```cpp
virtual bool System::Xml::XmlReader::ReadAttributeValue()=0
```

### Wartość zwracana

**true** jeśli istnieją węzły do zwrócenia. **false** jeśli czytnik nie jest ustawiony na węzeł atrybutu w momencie pierwszego wywołania lub jeśli wszystkie wartości atrybutu zostały odczytane. Pusty atrybut, na przykład **misc=""**, zwraca **true** z pojedynczym węzłem o wartości [String::Empty](../../../system/string/empty/).

## Zobacz także

* Klasa [XmlReader](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)