---
title: GetAttributeNode()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar XmlAttribute med det angivna namnet.
type: docs
weight: 248
url: /sv/system.xml/xmlelement/getattributenode/
---
## XmlElement::GetAttributeNode(String) metod

Returnerar [XmlAttribute](../../xmlattribute/) med det angivna namnet.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String name)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | [String](../../../system/string/) | Namnet på attributet som ska hämtas. Detta är ett kvalificerat namn. Det matchas mot **get_Name**-värdet för den matchande noden. |

### Returvärde

Den angivna [XmlAttribute](../../xmlattribute/) eller **nullptr** om ett matchande attribut inte hittades.

## XmlElement::GetAttributeNode(String, String) metod

Returnerar [XmlAttribute](../../xmlattribute/) med det angivna lokala namnet och namespace-URI.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String localName, String namespaceURI)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Det lokala namnet på attributet. |
| namespaceURI | [String](../../../system/string/) | Namespace-URI för attributet. |

### Returvärde

Den angivna [XmlAttribute](../../xmlattribute/) eller **nullptr** om ett matchande attribut inte hittades.

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [String](../../../system/string/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)