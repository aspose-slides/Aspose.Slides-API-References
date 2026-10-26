---
title: Item()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt de node op de opgegeven index op in de XmlNamedNodeMap.
type: docs
weight: 53
url: /nl/system.xml/xmlnamednodemap/item/
---
## XmlNamedNodeMap::Item(int32_t) methode


Haalt de node op de opgegeven index op in de [XmlNamedNodeMap](../).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::Item(int32_t index)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | De indexpositie van de node die opgehaald moet worden uit de [XmlNamedNodeMap](../). De index is nulgebaseerd; daarom is de index van de eerste node 0 en is de index van de laatste node [XmlNamedNodeMap::get_Count](../get_count/) - 1. |

### Retourwaarde

Het [XmlNode](../../xmlnode/) op de opgegeven index. Als **index** kleiner is dan 0 of groter dan of gelijk aan de [XmlNamedNodeMap::get_Count](../get_count/) waarde, wordt **nullptr** geretourneerd.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNode](../../xmlnode/)
* Klasse [XmlNamedNodeMap](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)