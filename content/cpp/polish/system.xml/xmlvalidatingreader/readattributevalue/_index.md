---
title: ReadAttributeValue()
second_title: Referencja API Aspose.Slides dla C++
description: Parsuje wartość atrybutu do jednego lub wielu węzłów Text, EntityReference lub EndEntity.
type: docs
weight: 508
url: /pl/system.xml/xmlvalidatingreader/readattributevalue/
---
## XmlValidatingReader::ReadAttributeValue() metoda


Parsuje wartość atrybutu do jednego lub wielu węzłów **[Text](../../../system.text/)**, **EntityReference** lub **EndEntity**.

```cpp
bool System::Xml::XmlValidatingReader::ReadAttributeValue() override
```


### Wartość zwracana

**true** jeśli istnieją węzły do zwrócenia. **false** jeśli czytnik nie jest ustawiony na węzeł atrybutu w momencie wywołania początkowego lub jeśli wszystkie wartości atrybutów zostały odczytane. Pusty atrybut, na przykład **misc=\"\"**, zwraca **true** z jednym węzłem o wartości [String::Empty](../../../system/string/empty/).

## Zobacz także

* Klasa [XmlValidatingReader](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)