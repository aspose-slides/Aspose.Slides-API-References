---
title: Item()
second_title: Aspose.Slides für C++ API-Referenz
description: Ruft einen Knoten am angegebenen Index ab.
type: docs
weight: 14
url: /de/system.xml/xmlnodelist/item/
---
## XmlNodeList::Item(int32_t) Methode


Ruft einen Knoten am angegebenen Index ab.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNodeList::Item(int32_t index)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Index in der Liste der Knoten. |

### Rückgabewert

Das [XmlNode](../../xmlnode/) mit dem angegebenen Index in der Sammlung. Wenn **index** größer oder gleich der Anzahl der Knoten in der Liste ist, liefert dies **nullptr**.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNode](../../xmlnode/)
* Klasse [XmlNodeList](../)
* Namensraum [System::Xml](../../)
* Library [Aspose.Slides](../../../)