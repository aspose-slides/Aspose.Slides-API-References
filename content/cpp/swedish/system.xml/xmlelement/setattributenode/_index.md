---
title: SetAttributeNode()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till det angivna XmlAttribute.
type: docs
weight: 261
url: /sv/system.xml/xmlelement/setattributenode/
---
## XmlElement::SetAttributeNode(SharedPtr\<XmlAttribute\>) method

Lägger till den angivna [XmlAttribute](../../xmlattribute/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(SharedPtr<XmlAttribute> newAttr)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newAttr | [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\> | Noden [XmlAttribute](../../xmlattribute/) att lägga till i attributsamlingen för detta element. |

### Returvärde

Om attributet ersätter ett befintligt attribut med samma namn, returneras det gamla [XmlAttribute](../../xmlattribute/); annars returneras **nullptr**.

## XmlElement::SetAttributeNode(String, String) method

Lägger till den angivna [XmlAttribute](../../xmlattribute/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(String localName, String namespaceURI)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Det lokala namnet på attributet. |
| namespaceURI | [String](../../../system/string/) | Namespace-URI:n för attributet. |

### Returvärde

[XmlAttribute](../../xmlattribute/) att lägga till.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [XmlElement](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)