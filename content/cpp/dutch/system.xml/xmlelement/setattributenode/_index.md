---
title: SetAttributeNode()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt het opgegeven XmlAttribute toe.
type: docs
weight: 261
url: /nl/system.xml/xmlelement/setattributenode/
---
## XmlElement::SetAttributeNode(SharedPtr\<XmlAttribute\>) methode

Voegt de opgegeven [XmlAttribute](../../xmlattribute/) toe.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(SharedPtr<XmlAttribute> newAttr)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newAttr | [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\> | De [XmlAttribute](../../xmlattribute/) node die moet worden toegevoegd aan de attribuutverzameling voor dit element. |

### Retourwaarde

Als het attribuut een bestaand attribuut met dezelfde naam vervangt, wordt de oude [XmlAttribute](../../xmlattribute/) geretourneerd; anders wordt **nullptr** geretourneerd.

## XmlElement::SetAttributeNode(String, String) methode

Voegt de opgegeven [XmlAttribute](../../xmlattribute/) toe.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(String localName, String namespaceURI)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| localName | [String](../../../system/string/) | De lokale naam van het attribuut. |
| namespaceURI | [String](../../../system/string/) | De namespace-URI van het attribuut. |

### Retourwaarde

De [XmlAttribute](../../xmlattribute/) die moet worden toegevoegd.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlAttribute](../../xmlattribute/)
* Klasse [XmlElement](../)
* Klasse [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)