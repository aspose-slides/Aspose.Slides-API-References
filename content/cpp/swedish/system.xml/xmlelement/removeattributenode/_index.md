---
title: RemoveAttributeNode()
second_title: Aspose.Slides för C++ API-referens
description: Tar bort den angivna XmlAttribute.
type: docs
weight: 274
url: /sv/system.xml/xmlelement/removeattributenode/
---
## XmlElement::RemoveAttributeNode(SharedPtr\<XmlAttribute\>) metod


Tar bort den angivna [XmlAttribute](../../xmlattribute/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(SharedPtr<XmlAttribute> oldAttr)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| oldAttr | [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\> | Noden [XmlAttribute](../../xmlattribute/) som ska tas bort. Om det borttagna attributet har ett standardvärde ersätts det omedelbart. |

### Return Value

Det borttagna [XmlAttribute](../../xmlattribute/) eller **nullptr** om **oldAttr** inte är en attributnod för [XmlElement](../).

## XmlElement::RemoveAttributeNode(String, String) metod


Tar bort den [XmlAttribute](../../xmlattribute/) som anges av det lokala namnet och namnrymdens URI. (Om det borttagna attributet har ett standardvärde ersätts det omedelbart).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(String localName, String namespaceURI)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Det lokala namnet på attributet. |
| namespaceURI | [String](../../../system/string/) | Namnområdets URI för attributet. |

### Return Value

Det borttagna [XmlAttribute](../../xmlattribute/) eller **nullptr** om [XmlElement](../) inte har en matchande attributnod.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlAttribute](../../xmlattribute/)
* Klass [XmlElement](../)
* Klass [String](../../../system/string/)
* Namnrymd [System::Xml](../../)
* Library [Aspose.Slides](../../../)