---
title: ReadAttributeValue()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Analizuje wartość atrybutu do jednego lub więcej węzłów Text, EntityReference lub EndEntity.
type: docs
weight: 560
url: /pl/system.xml/xmltextreader/readattributevalue/
---
## XmlTextReader::ReadAttributeValue() metoda

Analizuje wartość atrybutu do jednego lub więcej **[Text](../../../system.text/)**, **EntityReference**, lub **EndEntity** węzłów.

```cpp
bool System::Xml::XmlTextReader::ReadAttributeValue() override
```

### Wartość zwracana

**true** jeśli istnieją węzły do zwrócenia. **false** jeśli czytnik nie jest ustawiony na węzeł atrybutu podczas pierwszego wywołania lub jeśli wszystkie wartości atrybutu zostały odczytane. Pusty atrybut, taki jak **misc=\"\"**, zwraca **true** z jednym węzłem o wartości [String::Empty](../../../system/string/empty/).

## Zobacz także

* Klasa [XmlTextReader](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)