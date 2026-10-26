---
title: RemoveAttributeNode()
second_title: Aspose.Slides voor C++ API-referentie
description: Verwijdert de gespecificeerde XmlAttribute.
type: docs
weight: 274
url: /nl/system.xml/xmlelement/removeattributenode/
---
## XmlElement::RemoveAttributeNode(SharedPtr\<XmlAttribute\>) methode

Verwijdert de gespecificeerde [XmlAttribute](../../xmlattribute/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(SharedPtr<XmlAttribute> oldAttr)
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| oldAttr | [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\> | Het [XmlAttribute](../../xmlattribute/)-knooppunt om te verwijderen. Als het verwijderde attribuut een standaardwaarde heeft, wordt deze onmiddellijk vervangen. |

### Retourwaarde

De verwijderde [XmlAttribute](../../xmlattribute/) of **nullptr** als **oldAttr** geen attribuutknooppunt is van de [XmlElement](../).

## XmlElement::RemoveAttributeNode(String, String) methode

Verwijdert de [XmlAttribute](../../xmlattribute/) die is opgegeven door de lokale naam en namespace-URI. (Als het verwijderde attribuut een standaardwaarde heeft, wordt deze onmiddellijk vervangen).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(String localName, String namespaceURI)
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | De lokale naam van het attribuut. |
| namespaceURI | [String](../../../system/string/) | De namespace-URI van het attribuut. |

### Retourwaarde

De verwijderde [XmlAttribute](../../xmlattribute/) of **nullptr** als de [XmlElement](../) geen overeenkomend attribuutknooppunt heeft.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlAttribute](../../xmlattribute/)
* Klasse [XmlElement](../)
* Klasse [String](../../../system/string/)
* Naamruimte [System::Xml](../../)
* Library [Aspose.Slides](../../../)