---
title: GetNamedItem()
second_title: Aspose.Slides for C++ API Reference
description: Retrieves an XmlNode specified by name.
type: docs
weight: 14
url: /cpp/system.xml/xmlnamednodemap/getnameditem/
---
## XmlNamedNodeMap::GetNamedItem([String](../../../system/string/)) method


Retrieves an [XmlNode](../../xmlnode/) specified by name.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String name)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | The qualified name of the node to retrieve. It is matched against the [XmlNode::get_Name](../../xmlnode/get_name/) value of the matching node. |

### Return Value

An [XmlNode](../../xmlnode/) with the specified name or **nullptr** if a matching node is not found.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [String](../../../system/string/)
* Class [XmlNamedNodeMap](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
## XmlNamedNodeMap::GetNamedItem([String](../../../system/string/), [String](../../../system/string/)) method


Retrieves a node with the matching [XmlNode::get_LocalName](../../xmlnode/get_localname/) and [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) values.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String localName, String namespaceURI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | The local name of the node to retrieve. |
| namespaceURI | [String](../../../system/string/) | The namespace Uniform Resource Identifier (URI) of the node to retrieve. |

### Return Value

An [XmlNode](../../xmlnode/) with the matching local name and namespace URI or **nullptr** if a matching node was not found.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [String](../../../system/string/)
* Class [XmlNamedNodeMap](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
