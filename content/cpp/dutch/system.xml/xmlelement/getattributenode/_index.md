---
title: GetAttributeNode()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de XmlAttribute met de opgegeven naam.
type: docs
weight: 248
url: /nl/system.xml/xmlelement/getattributenode/
---
## XmlElement::GetAttributeNode(String) methode


Retourneert de [XmlAttribute](../../xmlattribute/) met de opgegeven naam.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String name)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | [String](../../../system/string/) | De naam van het attribuut dat opgehaald moet worden. Dit is een gekwalificeerde naam. Het wordt vergeleken met de **get_Name** waarde van het overeenkomende knooppunt. |

### Retourwaarde

De gespecificeerde [XmlAttribute](../../xmlattribute/) of **nullptr** als er geen overeenkomend attribuut werd gevonden.

## XmlElement::GetAttributeNode(String, String) methode


Retourneert de [XmlAttribute](../../xmlattribute/) met de opgegeven lokale naam en namespace-URI.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String localName, String namespaceURI)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| localName | [String](../../../system/string/) | De lokale naam van het attribuut. |
| namespaceURI | [String](../../../system/string/) | De namespace-URI van het attribuut. |

### Retourwaarde

De gespecificeerde [XmlAttribute](../../xmlattribute/) of **nullptr** als er geen overeenkomend attribuut werd gevonden.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlAttribute](../../xmlattribute/)
* Klasse [String](../../../system/string/)
* Klasse [XmlElement](../)
* Namespace [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)