---
title: CreateNode()
second_title: Aspose.Slides voor C++ API Referentie
description: "Maakt een XmlNode aan met het opgegeven XmlNodeType, XmlNode::get_Prefix, XmlDocument::get_Name en XmlNode::get_NamespaceURI."
type: docs
weight: 482
url: /nl/system.xml/xmldocument/createnode/
---
## XmlDocument::CreateNode(XmlNodeType, const String\&, const String\&, const String\&) method


Maakt een [XmlNode](../../xmlnode/) aan met het opgegeven XmlNodeType, [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_Name](../get_name/) en [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &prefix, const String &name, const String &namespaceURI)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | [XmlNodeType](../../xmlnodetype/) | Het XmlNodeType van het nieuwe knooppunt. |
| prefix | const [String](../../../system/string/)\& | Het voorvoegsel van het nieuwe knooppunt. |
| name | const [String](../../../system/string/)\& | De lokale naam van het nieuwe knooppunt. |
| namespaceURI | const [String](../../../system/string/)\& | De namespace-URI van het nieuwe knooppunt. |

### Retourwaarde

De nieuwe [XmlNode](../../xmlnode/).

## XmlDocument::CreateNode(const String\&, const String\&, const String\&) method


Maakt een [XmlNode](../../xmlnode/) aan met het opgegeven knooppunttype, [XmlDocument::get_Name](../get_name/) en [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(const String &nodeTypeString, const String &name, const String &namespaceURI)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| nodeTypeString | const [String](../../../system/string/)\& | [String](../../../system/string/) versie van het XmlNodeType van het nieuwe knooppunt. Deze parameter moet een van de waarden zijn die in de onderstaande tabel staan. |
| name | const [String](../../../system/string/)\& | De gekwalificeerde naam van het nieuwe knooppunt. Als de naam een dubbele punt bevat, wordt deze geparseerd in [XmlNode::get_Prefix](../../xmlnode/get_prefix/)- en [XmlDocument::get_LocalName](../get_localname/)-componenten. |
| namespaceURI | const [String](../../../system/string/)\& | De namespace-URI van het nieuwe knooppunt. |

### Retourwaarde

De nieuwe [XmlNode](../../xmlnode/).
## Opmerkingen



De parameter **nodeTypeString** is hoofdlettergevoelig en moet een van de waarden in de volgende tabel zijn: 

| nodeTypeString| XmlNodeType |
| --- | --- |
| attribute| [Attribute](../../../system/attribute/)|
| cdatasection| CDATA |
| comment| Comment |
| document| Document |
| documentfragment| DocumentFragment |
| documenttype| DocumentType |
| element| Element |
| entityreference| EntityReference |
| processinginstruction| ProcessingInstruction |
| significantwhitespace| SignificantWhitespace |
| text| [Text](../../../system.text/)|
| whitespace| Whitespace |


## XmlDocument::CreateNode(XmlNodeType, const String\&, const String\&) method


Maakt een [XmlNode](../../xmlnode/) aan met het opgegeven XmlNodeType, [XmlDocument::get_Name](../get_name/) en [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &name, const String &namespaceURI)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | [XmlNodeType](../../xmlnodetype/) | Het XmlNodeType van het nieuwe knooppunt. |
| name | const [String](../../../system/string/)\& | De gekwalificeerde naam van het nieuwe knooppunt. Als de naam een dubbele punt bevat, wordt deze geparseerd in [XmlNode::get_Prefix](../../xmlnode/get_prefix/)- en [XmlDocument::get_LocalName](../get_localname/)-componenten. |
| namespaceURI | const [String](../../../system/string/)\& | De namespace-URI van het nieuwe knooppunt. |

### Retourwaarde

De nieuwe [XmlNode](../../xmlnode/).

## Zie ook

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNode](../../xmlnode/)
* Klasse [String](../../../system/string/)
* Klasse [XmlDocument](../)
* Namespace [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)