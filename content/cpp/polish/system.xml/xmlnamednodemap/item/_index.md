---
title: Item()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Pobiera węzeł o określonym indeksie w XmlNamedNodeMap.
type: docs
weight: 53
url: /pl/system.xml/xmlnamednodemap/item/
---
## XmlNamedNodeMap::Item(int32_t) metoda


Pobiera węzeł o podanym indeksie w [XmlNamedNodeMap](../).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::Item(int32_t index)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Pozycja indeksu węzła do pobrania z [XmlNamedNodeMap](../). Indeks jest zerowy; dlatego indeks pierwszego węzła wynosi 0, a indeks ostatniego węzła to [XmlNamedNodeMap::get_Count](../get_count/) - 1. |

### Wartość zwracana

[XmlNode](../../xmlnode/) o podanym indeksie. Jeśli **index** jest mniejszy niż 0 lub większy lub równy wartości [XmlNamedNodeMap::get_Count](../get_count/), zwracane jest **nullptr**.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlNode](../../xmlnode/)
* Klasa [XmlNamedNodeMap](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)