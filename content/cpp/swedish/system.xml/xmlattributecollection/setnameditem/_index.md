---
title: SetNamedItem()
second_title: Aspose.Slides för C++ API-referens
description: "Lägger till en XmlNode med hjälp av dess XmlNode::get_Name-resultat."
type: docs
weight: 14
url: /sv/system.xml/xmlattributecollection/setnameditem/
---
## XmlAttributeCollection::SetNamedItem(SharedPtr\<XmlNode\>) metod

Lägger till en [XmlNode](../../xmlnode/) med dess [XmlNode::get_Name](../../xmlnode/get_name/) resultat.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttributeCollection::SetNamedItem(SharedPtr<XmlNode> node) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | En attribut node att lagra i den här samlingen. node kommer senare att vara åtkomlig med hjälp av namnet på node. Om en node med det namnet redan finns i samlingen, ersätts den med den nya; annars läggs node till i slutet av samlingen. |

### Returvärde

Om **node** ersätter en befintlig node med samma namn, returneras den gamla node; annars returneras den tillagda node.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlNode](../../xmlnode/)
* Klass [XmlAttributeCollection](../)
* Namnrymd [System::Xml](../../)
* Library [Aspose.Slides](../../../)