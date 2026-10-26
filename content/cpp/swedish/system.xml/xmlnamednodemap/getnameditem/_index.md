---
title: GetNamedItem()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar en XmlNode specificerad med namn.
type: docs
weight: 14
url: /sv/system.xml/xmlnamednodemap/getnameditem/
---
## XmlNamedNodeMap::GetNamedItem(String) metod

Hämtar en [XmlNode](../../xmlnode/) specificerad med namn.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String name)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | [String](../../../system/string/) | Det kvalificerade namnet på noden som ska hämtas. Det matchas mot [XmlNode::get_Name](../../xmlnode/get_name/)-värdet för den matchande noden. |

### Returvärde

En [XmlNode](../../xmlnode/) med det angivna namnet eller **nullptr** om ingen matchande nod hittas.

## XmlNamedNodeMap::GetNamedItem(String, String) metod

Hämtar en nod med de matchande [XmlNode::get_LocalName](../../xmlnode/get_localname/)- och [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/)-värdena.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String localName, String namespaceURI)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Det lokala namnet på noden som ska hämtas. |
| namespaceURI | [String](../../../system/string/) | Namespace Uniform Resource Identifier (URI) för noden som ska hämtas. |

### Returvärde

En [XmlNode](../../xmlnode/) med det matchande lokala namnet och namespace-URI:n eller **nullptr** om ingen matchande nod hittades.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlNode](../../xmlnode/)
* Klass [String](../../../system/string/)
* Klass [XmlNamedNodeMap](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)