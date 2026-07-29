---
title: SetNamedItem()
second_title: Aspose.Slides för C++ API-referens
description: "Lägger till en XmlNode med dess XmlNode::get_Name-värde."
type: docs
weight: 27
url: /sv/system.xml/xmlnamednodemap/setnameditem/
---
## XmlNamedNodeMap::SetNamedItem(SharedPtr\<XmlNode\>) metod

Lägger till en [XmlNode](../../xmlnode/) med dess [XmlNode::get_Name](../../xmlnode/get_name/) värde.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::SetNamedItem(SharedPtr<XmlNode> node)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | En [XmlNode](../../xmlnode/) att lagra i [XmlNamedNodeMap](../). Om en nod med det namnet redan finns i kartan, ersätts den med den nya. |

### Returvärde

Om **node** ersätter en befintlig nod med samma namn, returneras den gamla noden; annars returneras **nullptr**.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlNode](../../xmlnode/)
* Klass [XmlNamedNodeMap](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)