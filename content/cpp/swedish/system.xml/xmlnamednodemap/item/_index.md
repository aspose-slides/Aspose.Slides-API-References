---
title: Item()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar noden på det angivna indexet i XmlNamedNodeMap.
type: docs
weight: 53
url: /sv/system.xml/xmlnamednodemap/item/
---
## XmlNamedNodeMap::Item(int32_t) metod

Hämtar noden på det angivna indexet i [XmlNamedNodeMap](../).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::Item(int32_t index)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Indexpositionen för noden som ska hämtas från [XmlNamedNodeMap](../). Indexet är nollbaserat; därför är indexet för den första noden 0 och indexet för den sista noden [XmlNamedNodeMap::get_Count](../get_count/) - 1. |

### Returvärde

[XmlNode](../../xmlnode/) på det angivna indexet. Om **index** är mindre än 0 eller större än eller lika med [XmlNamedNodeMap::get_Count](../get_count/)-värdet, returneras **nullptr**.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlNode](../../xmlnode/)
* Klass [XmlNamedNodeMap](../)
* Namnrymd [System::Xml](../../)
* Library [Aspose.Slides](../../../)