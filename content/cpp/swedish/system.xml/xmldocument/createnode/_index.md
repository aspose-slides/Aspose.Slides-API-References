---
title: CreateNode()
second_title: Aspose.Slides för C++ API-referens
description: "Skapar ett XmlNode med den angivna XmlNodeType, XmlNode::get_Prefix, XmlDocument::get_Name och XmlNode::get_NamespaceURI."
type: docs
weight: 482
url: /sv/system.xml/xmldocument/createnode/
---
## XmlDocument::CreateNode(XmlNodeType, const String\&, const String\&, const String\&) metod


Skapar en [XmlNode](../../xmlnode/) med den angivna XmlNodeType, [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_Name](../get_name/) och [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &prefix, const String &name, const String &namespaceURI)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | [XmlNodeType](../../xmlnodetype/) | The XmlNodeType of the new node. |
| prefix | const [String](../../../system/string/)\& | The prefix of the new node. |
| name | const [String](../../../system/string/)\& | The local name of the new node. |
| namespaceURI | const [String](../../../system/string/)\& | The namespace URI of the new node. |

### Returvärde

The new [XmlNode](../../xmlnode/).

## XmlDocument::CreateNode(const String\&, const String\&, const String\&) metod


Skapar ett [XmlNode](../../xmlnode/) med den angivna nodtypen, [XmlDocument::get_Name](../get_name/) och [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(const String &nodeTypeString, const String &name, const String &namespaceURI)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nodeTypeString | const [String](../../../system/string/)\& | [String](../../../system/string/) version of the XmlNodeType of the new node. This parameter must be one of the values listed in the table below. |
| name | const [String](../../../system/string/)\& | The qualified name of the new node. If the name contains a colon, it is parsed into [XmlNode::get_Prefix](../../xmlnode/get_prefix/) and [XmlDocument::get_LocalName](../get_localname/) components. |
| namespaceURI | const [String](../../../system/string/)\& | The namespace URI of the new node. |

### Returvärde

The new [XmlNode](../../xmlnode/).

## Anmärkningar



Parametern **nodeTypeString** är skiftlägeskänslig och måste vara ett av värdena i följande tabell: 

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


## XmlDocument::CreateNode(XmlNodeType, const String\&, const String\&) metod


Skapar ett [XmlNode](../../xmlnode/) med den angivna XmlNodeType, [XmlDocument::get_Name](../get_name/) och [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &name, const String &namespaceURI)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | [XmlNodeType](../../xmlnodetype/) | The XmlNodeType of the new node. |
| name | const [String](../../../system/string/)\& | The qualified name of the new node. If the name contains a colon then it is parsed into [XmlNode::get_Prefix](../../xmlnode/get_prefix/) and [XmlDocument::get_LocalName](../get_localname/) components. |
| namespaceURI | const [String](../../../system/string/)\& | The namespace URI of the new node. |

### Returvärde

The new [XmlNode](../../xmlnode/).

## Se också

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlNode](../../xmlnode/)
* Klass [String](../../../system/string/)
* Klass [XmlDocument](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)