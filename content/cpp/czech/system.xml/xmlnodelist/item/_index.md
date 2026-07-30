---
title: Item()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Získá uzel na zadaném indexu.
type: docs
weight: 14
url: /cs/system.xml/xmlnodelist/item/
---
## XmlNodeList::Item(int32_t) metoda

Získá uzel na zadaném indexu.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNodeList::Item(int32_t index)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Index založený na nule do seznamu uzlů. |

### Návratová hodnota

Objekt [XmlNode](../../xmlnode/) s určeným indexem ve sbírce. Pokud je **index** větší nebo roven počtu uzlů v seznamu, tento vrací **nullptr**.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlNode](../../xmlnode/)
* Třída [XmlNodeList](../)
* Jmenný prostor [System::Xml](../../)
* Library [Aspose.Slides](../../../)