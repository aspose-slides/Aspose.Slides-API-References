---
title: Item()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar en nod på det angivna indexet.
type: docs
weight: 14
url: /sv/system.xml/xmlnodelist/item/
---
## XmlNodeList::Item(int32_t) method


Hämtar en nod på det angivna indexet.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNodeList::Item(int32_t index)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade indexet i listan av noder. |

### Returvärde

Det [XmlNode](../../xmlnode/) med det angivna indexet i samlingen. Om **index** är större än eller lika med antalet noder i listan returneras **nullptr**.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlNode](../../xmlnode/)
* Klass [XmlNodeList](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)