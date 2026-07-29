---
title: GetElementsByTagName()
second_title: Aspose.Slides för C++ API-referens
description: "Returnerar en XmlNodeList som innehåller en lista med alla nedärvda element som matchar den angivna XmlElement::get_Name."
type: docs
weight: 287
url: /sv/system.xml/xmlelement/getelementsbytagname/
---
## XmlElement::GetElementsByTagName(String) metod


Returnerar en [XmlNodeList](../../xmlnodelist/) som innehåller en lista med alla nedärvda element som matchar den angivna [XmlElement::get_Name](../get_name/).

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String name)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | [String](../../../system/string/) | Namnet på taggen att matcha. Detta är ett kvalificerat namn. Det matchas mot **get_Name**-värdet för den matchande noden. Asterisken (*) är ett specialvärde som matchar alla taggar. |

### Returvärde

En [XmlNodeList](../../xmlnodelist/) som innehåller en lista med alla matchande noder. Listan är tom om det inte finns några matchande noder.

## XmlElement::GetElementsByTagName(String, String) metod


Returnerar en [XmlNodeList](../../xmlnodelist/) som innehåller en lista med alla nedärvda element som matchar de angivna [XmlElement::get_LocalName](../get_localname/)- och [XmlElement::get_NamespaceURI](../get_namespaceuri/)-värdena.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String localName, String namespaceURI)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Det lokala namnet att matcha. Asterisken (*) är ett specialvärde som matchar alla taggar. |
| namespaceURI | [String](../../../system/string/) | Den namnrymds-URI som ska matchas. |

### Returvärde

En [XmlNodeList](../../xmlnodelist/) som innehåller en lista med alla matchande noder. Listan är tom om det inte finns några matchande noder.

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [XmlNodeList](../../xmlnodelist/)
* Klass [String](../../../system/string/)
* Klass [XmlElement](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)