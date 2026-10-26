---
title: RemoveNamedItem()
second_title: Aspose.Slides voor C++ API-referentie
description: Verwijdert het knooppunt uit de XmlNamedNodeMap.
type: docs
weight: 40
url: /nl/system.xml/xmlnamednodemap/removenameditem/
---
## XmlNamedNodeMap::RemoveNamedItem(String) methode

Verwijdert het knooppunt uit de [XmlNamedNodeMap](../).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String name)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | [String](../../../system/string/) | De gekwalificeerde naam van het te verwijderen knooppunt. De naam wordt vergeleken met de [XmlNode::get_Name](../../xmlnode/get_name/) waarde van het overeenkomende knooppunt. |

### Retourwaarde

De [XmlNode](../../xmlnode/) verwijderd uit deze [XmlNamedNodeMap](../) of **nullptr** als er geen overeenkomend knooppunt werd gevonden.

## XmlNamedNodeMap::RemoveNamedItem(String, String) methode

Verwijdert een knooppunt met de overeenkomende [XmlNode::get_LocalName](../../xmlnode/get_localname/) en [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) waarden.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String localName, String namespaceURI)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| localName | [String](../../../system/string/) | De lokale naam van het te verwijderen knooppunt. |
| namespaceURI | [String](../../../system/string/) | De naamruimte-URI van het te verwijderen knooppunt. |

### Retourwaarde

De [XmlNode](../../xmlnode/) verwijderd of **nullptr** als er geen overeenkomend knooppunt werd gevonden.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNode](../../xmlnode/)
* Klasse [String](../../../system/string/)
* Klasse [XmlNamedNodeMap](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)