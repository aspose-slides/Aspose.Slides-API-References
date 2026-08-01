---
title: SetNamedItem()
second_title: Aspose.Slides voor C++ API-referentie
description: "Voegt een XmlNode toe met behulp van de waarde van XmlNode::get_Name."
type: docs
weight: 27
url: /nl/system.xml/xmlnamednodemap/setnameditem/
---
## XmlNamedNodeMap::SetNamedItem(SharedPtr\<XmlNode\>) methode

Voegt een [XmlNode](../../xmlnode/) toe met behulp van zijn [XmlNode::get_Name](../../xmlnode/get_name/) waarde.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::SetNamedItem(SharedPtr<XmlNode> node)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Een [XmlNode](../../xmlnode/) om op te slaan in de [XmlNamedNodeMap](../). Als een node met die naam al aanwezig is in de map, wordt deze vervangen door de nieuwe. |

### Retourwaarde

Als de **node** een bestaande node met dezelfde naam vervangt, wordt de oude node geretourneerd; anders wordt **nullptr** geretourneerd.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNode](../../xmlnode/)
* Klasse [XmlNamedNodeMap](../)
* Namespace [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)