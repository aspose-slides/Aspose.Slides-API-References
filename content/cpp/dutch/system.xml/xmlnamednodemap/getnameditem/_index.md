---
title: GetNamedItem()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt een XmlNode op die op naam is gespecificeerd.
type: docs
weight: 14
url: /nl/system.xml/xmlnamednodemap/getnameditem/
---
## XmlNamedNodeMap::GetNamedItem(String) methode


Haalt een [XmlNode](../../xmlnode/) op die door naam is gespecificeerd.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String name)
```


### Argumenten

| Parameter | Type | Omschrijving |
| --- | --- | --- |
| name | [String](../../../system/string/) | De gekwalificeerde naam van de node die opgehaald moet worden. Deze wordt vergeleken met de [XmlNode::get_Name](../../xmlnode/get_name/)-waarde van de overeenkomende node. |

### Return Value

Een [XmlNode](../../xmlnode/) met de opgegeven naam of **nullptr** als er geen overeenkomende node wordt gevonden.

## XmlNamedNodeMap::GetNamedItem(String, String) methode


Haalt een node op met de overeenkomende [XmlNode::get_LocalName](../../xmlnode/get_localname/)- en [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/)-waarden.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String localName, String namespaceURI)
```


### Argumenten

| Parameter | Type | Omschrijving |
| --- | --- | --- |
| localName | [String](../../../system/string/) | De lokale naam van de node die opgehaald moet worden. |
| namespaceURI | [String](../../../system/string/) | De namespace Uniform Resource Identifier (URI) van de node die opgehaald moet worden. |

### Return Value

Een [XmlNode](../../xmlnode/) met de overeenkomende lokale naam en namespace-URI of **nullptr** als er geen overeenkomende node werd gevonden.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNode](../../xmlnode/)
* Klasse [String](../../../system/string/)
* Klasse [XmlNamedNodeMap](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)