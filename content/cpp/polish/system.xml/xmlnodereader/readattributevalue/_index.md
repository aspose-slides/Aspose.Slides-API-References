---
title: ReadAttributeValue()
second_title: Aspose.Slides dla C++ referencja API
description: Analizuje wartość atrybutu i zamienia ją na jeden lub więcej węzłów Text, EntityReference lub EndEntity.
type: docs
weight: 430
url: /pl/system.xml/xmlnodereader/readattributevalue/
---
## XmlNodeReader::ReadAttributeValue() metoda


Przetwarza wartość atrybutu na jeden lub więcej węzłów **[Text](../../../system.text/)**, **EntityReference** lub **EndEntity**.

```cpp
bool System::Xml::XmlNodeReader::ReadAttributeValue() override
```


### Wartość zwracana

**true** jeśli są węzły do zwrócenia. **false** jeśli czytnik nie jest ustawiony na węzeł atrybutu w momencie pierwszego wywołania lub jeśli wszystkie wartości atrybutu zostały odczytane. Pusty atrybut, taki jak **misc=\"\"**, zwraca **true** z pojedynczym węzłem o wartości [String::Empty](../../../system/string/empty/).

## Zobacz także

* Klasa [XmlNodeReader](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)