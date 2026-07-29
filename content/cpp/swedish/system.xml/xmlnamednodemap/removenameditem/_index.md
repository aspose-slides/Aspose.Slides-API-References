---
title: RemoveNamedItem()
second_title: Aspose.Slides för C++ API-referens
description: Tar bort noden från XmlNamedNodeMap.
type: docs
weight: 40
url: /sv/system.xml/xmlnamednodemap/removenameditem/
---
## XmlNamedNodeMap::RemoveNamedItem(String) metod

Tar bort noden från [XmlNamedNodeMap](../).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String name)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | [String](../../../system/string/) | Det kvalificerade namnet på noden som ska tas bort. Namnet matchas mot [XmlNode::get_Name](../../xmlnode/get_name/)-värdet för den matchande noden. |

### Return Value

Den [XmlNode](../../xmlnode/) som togs bort från denna [XmlNamedNodeMap](../) eller **nullptr** om ingen matchande nod hittades.

## XmlNamedNodeMap::RemoveNamedItem(String, String) metod

Tar bort en nod med de matchande [XmlNode::get_LocalName](../../xmlnode/get_localname/) och [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) värdena.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String localName, String namespaceURI)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Det lokala namnet på noden som ska tas bort. |
| namespaceURI | [String](../../../system/string/) | Namespace-URI för noden som ska tas bort. |

### Return Value

[XmlNode](../../xmlnode/) som togs bort eller **nullptr** om ingen matchande nod hittades.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [String](../../../system/string/)
* Class [XmlNamedNodeMap](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)