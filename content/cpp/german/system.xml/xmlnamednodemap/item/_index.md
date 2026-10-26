---
title: Item()
second_title: Aspose.Slides für C++ API-Referenz
description: Ruft den Knoten am angegebenen Index im XmlNamedNodeMap ab.
type: docs
weight: 53
url: /de/system.xml/xmlnamednodemap/item/
---
## XmlNamedNodeMap::Item(int32_t) Methode


Ruft den Knoten am angegebenen Index im [XmlNamedNodeMap](../) ab.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::Item(int32_t index)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Die Indexposition des abzurufenden Knotens aus dem [XmlNamedNodeMap](../). Der Index ist nullbasiert; daher ist der Index des ersten Knotens 0 und der Index des letzten Knotens [XmlNamedNodeMap::get_Count](../get_count/) - 1. |

### Rückgabewert

Der [XmlNode](../../xmlnode/) am angegebenen Index. Wenn **index** kleiner als 0 oder größer/gleich dem [XmlNamedNodeMap::get_Count](../get_count/)-Wert ist, wird **nullptr** zurückgegeben.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNode](../../xmlnode/)
* Klasse [XmlNamedNodeMap](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)