---
title: CreateNode()
second_title: Aspose.Slides for C++ API Reference
description: "Creates a XmlNode with the specified XmlNodeType, XmlNode::get_Prefix, XmlDocument::get_Name, and XmlNode::get_NamespaceURI."
type: docs
weight: 482
url: /cpp/system.xml/xmldocument/createnode/
---
## XmlDocument::CreateNode(XmlNodeType, const String\&, const String\&, const String\&) method


Creates a [XmlNode](../../xmlnode/) with the specified XmlNodeType, [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_Name](../get_name/), and [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &prefix, const String &name, const String &namespaceURI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | [XmlNodeType](../../xmlnodetype/) | The XmlNodeType of the new node. |
| prefix | const [String](../../../system/string/)\& | The prefix of the new node. |
| name | const [String](../../../system/string/)\& | The local name of the new node. |
| namespaceURI | const [String](../../../system/string/)\& | The namespace URI of the new node. |

### Return Value

The new [XmlNode](../../xmlnode/).

## XmlDocument::CreateNode(const String\&, const String\&, const String\&) method


Creates an [XmlNode](../../xmlnode/) with the specified node type, [XmlDocument::get_Name](../get_name/), and [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(const String &nodeTypeString, const String &name, const String &namespaceURI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| nodeTypeString | const [String](../../../system/string/)\& | [String](../../../system/string/) version of the XmlNodeType of the new node. This parameter must be one of the values listed in the table below. |
| name | const [String](../../../system/string/)\& | The qualified name of the new node. If the name contains a colon, it is parsed into [XmlNode::get_Prefix](../../xmlnode/get_prefix/) and [XmlDocument::get_LocalName](../get_localname/) components. |
| namespaceURI | const [String](../../../system/string/)\& | The namespace URI of the new node. |

### Return Value

The new [XmlNode](../../xmlnode/).
## Remarks



The **nodeTypeString** parameter is case sensitive and must be one of the values in the following table: 

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


Creates an [XmlNode](../../xmlnode/) with the specified XmlNodeType, [XmlDocument::get_Name](../get_name/), and [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &name, const String &namespaceURI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | [XmlNodeType](../../xmlnodetype/) | The XmlNodeType of the new node. |
| name | const [String](../../../system/string/)\& | The qualified name of the new node. If the name contains a colon then it is parsed into [XmlNode::get_Prefix](../../xmlnode/get_prefix/) and [XmlDocument::get_LocalName](../get_localname/) components. |
| namespaceURI | const [String](../../../system/string/)\& | The namespace URI of the new node. |

### Return Value

The new [XmlNode](../../xmlnode/).

## See Also

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)