---
title: CreateAttribute()
second_title: Aspose.Slides för C++ API-referens
description: Skapar ett XmlAttribute med det angivna namnet.
type: docs
weight: 274
url: /sv/system.xml/xmldocument/createattribute/
---
## XmlDocument::CreateAttribute(const String\&) metod


Skapar en [XmlAttribute](../../xmlattribute/) med det angivna namnet.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &name)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Det kvalificerade namnet på attributet. Om namnet innehåller ett kolon speglar [XmlNode::get_Prefix](../../xmlnode/get_prefix/)-värdet delen av namnet som föregår det första kolonet och [XmlDocument::get_LocalName](../get_localname/)-värdet speglar delen av namnet som följer efter det första kolonet. [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) förblir tomt om inte prefixet är ett känt inbyggt prefix såsom **xmlns**. I detta fall har get_NamespaceURI värdet [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/). |

### Returvärde

Den nya [XmlAttribute](../../xmlattribute/).

## XmlDocument::CreateAttribute(const String\&, const String\&) metod


Skapar en [XmlAttribute](../../xmlattribute/) med det angivna kvalificerade namnet och [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &qualifiedName, const String &namespaceURI)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| qualifiedName | const [String](../../../system/string/)\& | Det kvalificerade namnet på attributet. Om namnet innehåller ett kolon kommer [XmlNode::get_Prefix](../../xmlnode/get_prefix/)-värdet att spegla delen av namnet som föregår kolonet och [XmlDocument::get_LocalName](../get_localname/)-värdet att spegla delen av namnet efter kolonet. |
| namespaceURI | const [String](../../../system/string/)\& | NamespaceURI för attributet. Om det kvalificerade namnet inkluderar ett prefix **xmlns**, måste denna parameter vara [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/). |

### Returvärde

Den nya [XmlAttribute](../../xmlattribute/).

## XmlDocument::CreateAttribute(const String\&, const String\&, const String\&) metod


Skapar en [XmlAttribute](../../xmlattribute/) med de angivna [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_LocalName](../get_localname/) och [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &prefix, const String &localName, const String &namespaceURI)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Prefixet för attributet (om något). [String::Empty](../../../system/string/empty/) och **nullptr** är ekvivalenta. |
| localName | const [String](../../../system/string/)\& | Det lokala namnet på attributet. |
| namespaceURI | const [String](../../../system/string/)\& | Namespace-URI för attributet (om någon). [String::Empty](../../../system/string/empty/) och **nullptr** är ekvivalenta. Om **prefix** är **xmlns**, måste denna parameter vara [http://www.w3.org/2000/xmlns/;](http://www.w3.org/2000/xmlns/;) annars kastas ett undantag. |

### Returvärde

Den nya [XmlAttribute](../../xmlattribute/).

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)