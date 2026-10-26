---
title: Item()
second_title: Aspose.Slides pro C++ referenci API
description: Získá uzel na zadaném indexu v XmlNamedNodeMap.
type: docs
weight: 53
url: /cs/system.xml/xmlnamednodemap/item/
---
## XmlNamedNodeMap::Item(int32_t) metoda


Získá uzel na zadaném indexu v [XmlNamedNodeMap](../).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::Item(int32_t index)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Pozice indexu uzlu, který se má získat z [XmlNamedNodeMap](../). Index je nulový; tudíž index prvního uzlu je 0 a index posledního uzlu je [XmlNamedNodeMap::get_Count](../get_count/) - 1. |

### Návratová hodnota

[XmlNode](../../xmlnode/) na zadaném indexu. Pokud je **index** menší než 0 nebo větší nebo roven hodnotě [XmlNamedNodeMap::get_Count](../get_count/), je vráceno **nullptr**.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlNode](../../xmlnode/)
* Třída [XmlNamedNodeMap](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)