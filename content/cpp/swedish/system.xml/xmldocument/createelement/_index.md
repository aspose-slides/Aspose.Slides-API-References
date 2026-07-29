---
title: CreateElement()
second_title: Aspose.Slides för C++ API-referens
description: Skapar ett element med det angivna namnet.
type: docs
weight: 339
url: /sv/system.xml/xmldocument/createelement/
---
## XmlDocument::CreateElement(const String\&) method


Skapar ett element med det angivna namnet.

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &name)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Det kvalificerade namnet på elementet. Om namnet innehåller ett kolon så reflekterar [XmlNode::get_Prefix](../../xmlnode/get_prefix/)-värdet delen av namnet som föregår kolonet och [XmlDocument::get_LocalName](../get_localname/)-värdet reflekterar delen av namnet som följer kolonet. Det kvalificerade namnet får inte inkludera ett prefix av **xmlns**. |

### Returvärde

Det nya [XmlElement](../../xmlelement/).

## XmlDocument::CreateElement(const String\&, const String\&) method


Skapar ett [XmlElement](../../xmlelement/) med det kvalificerade namnet och [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &qualifiedName, const String &namespaceURI)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| qualifiedName | const [String](../../../system/string/)\& | Det kvalificerade namnet på elementet. Om namnet innehåller ett kolon så reflekterar [XmlNode::get_Prefix](../../xmlnode/get_prefix/)-värdet delen av namnet som föregår kolonet och [XmlDocument::get_LocalName](../get_localname/)-värdet reflekterar delen av namnet som följer kolonet. Det kvalificerade namnet får inte inkludera ett prefix av **xmlns**. |
| namespaceURI | const [String](../../../system/string/)\& | Namnutrymmet URI för elementet. |

### Returvärde

Det nya [XmlElement](../../xmlelement/).

## XmlDocument::CreateElement(const String\&, const String\&, const String\&) method


Skapar ett element med den angivna [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_LocalName](../get_localname/) och [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &prefix, const String &localName, const String &namespaceURI)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Prefixet för det nya elementet (om någon). [String::Empty](../../../system/string/empty/) och **nullptr** är ekvivalenta. |
| localName | const [String](../../../system/string/)\& | Det lokala namnet på det nya elementet. |
| namespaceURI | const [String](../../../system/string/)\& | Namnutrymmet URI för det nya elementet (om någon). [String::Empty](../../../system/string/empty/) och **nullptr** är ekvivalenta. |

### Returvärde

Det nya [XmlElement](../../xmlelement/).

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlElement](../../xmlelement/)
* Klass [String](../../../system/string/)
* Klass [XmlDocument](../)
* Namnutrymme [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)