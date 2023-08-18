---
title: RemoveNamedItem()
second_title: Aspose.Slides for C++ API Reference
description: Removes the node from the XmlNamedNodeMap.
type: docs
weight: 40
url: /system.xml/xmlnamednodemap/removenameditem/
---
## XmlNamedNodeMap::RemoveNamedItem(String) method


Removes the node from the [XmlNamedNodeMap](../).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String name)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | The qualified name of the node to remove. The name is matched against the [XmlNode::get_Name](../../xmlnode/get_name/) value of the matching node. |

### Return Value

The [XmlNode](../../xmlnode/) removed from this [XmlNamedNodeMap](../) or **nullptr** if a matching node was not found.

## XmlNamedNodeMap::RemoveNamedItem(String, String) method


Removes a node with the matching [XmlNode::get_LocalName](../../xmlnode/get_localname/) and [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) values.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String localName, String namespaceURI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | The local name of the node to remove. |
| namespaceURI | [String](../../../system/string/) | The namespace URI of the node to remove. |

### Return Value

The [XmlNode](../../xmlnode/) removed or **nullptr** if a matching node was not found.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [String](../../../system/string/)
* Class [XmlNamedNodeMap](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)