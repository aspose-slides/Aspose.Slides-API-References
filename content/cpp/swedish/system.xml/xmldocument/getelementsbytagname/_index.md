---
title: GetElementsByTagName()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar en XmlNodeList som innehåller en lista med alla underordnade element som matchar det angivna namnet.
type: docs
weight: 443
url: /sv/system.xml/xmldocument/getelementsbytagname/
---
## XmlDocument::GetElementsByTagName(String) metod

Returnerar en [XmlNodeList](../../xmlnodelist/) som innehåller en lista med alla underordnade element som matchar det angivna namnet.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String name)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | [String](../../../system/string/) | Det kvalificerade namnet att matcha. Det matchas mot **get_Name**-värdet för den matchande noden. Det speciella värdet **"*"** matchar alla taggar. |

### Returvärde

En [XmlNodeList](../../xmlnodelist/) som innehåller en lista med alla matchande noder. Om inga noder matchar **name**, kommer den returnerade samlingen att vara tom.

## XmlDocument::GetElementsByTagName(String, String) metod

Returnerar en [XmlNodeList](../../xmlnodelist/) som innehåller en lista med alla underordnade element som matchar den angivna [XmlDocument::get_LocalName](../get_localname/) och [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String localName, String namespaceURI)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Det LocalName att matcha. Det speciella värdet **"*"** matchar alla taggar. |
| namespaceURI | [String](../../../system/string/) | NamespaceURI att matcha. |

### Returvärde

En [XmlNodeList](../../xmlnodelist/) som innehåller en lista med alla matchande noder. Om inga noder matchar den angivna **localName** och **namespaceURI**, kommer den returnerade samlingen att vara tom.

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [XmlNodeList](../../xmlnodelist/)
* Klass [String](../../../system/string/)
* Klass [XmlDocument](../)
* Namnrum [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)