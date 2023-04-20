---
title: SelectDescendants()
second_title: Aspose.Slides for C++ API Reference
description: Selects all the descendant nodes of the current node that have a matching XPathNodeType.
type: docs
weight: 859
url: /cpp/system.xml.xpath/xpathnavigator/selectdescendants/
---
## XPathNavigator::SelectDescendants(XPathNodeType, bool) method


Selects all the descendant nodes of the current node that have a matching XPathNodeType.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(XPathNodeType type, bool matchSelf)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | The XPathNodeType of the descendant nodes. |
| matchSelf | **bool** | **true** to include the context node in the selection; otherwise, **false**. |

### Return Value

An [XPathNodeIterator](../../xpathnodeiterator/) that contains the selected nodes.

## XPathNavigator::SelectDescendants(String, String, bool) method


Selects all the descendant nodes of the current node with the local name and namespace URI specified.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectDescendants(String name, String namespaceURI, bool matchSelf)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | The local name of the descendant nodes. |
| namespaceURI | [String](../../../system/string/) | The namespace URI of the descendant nodes. |
| matchSelf | **bool** | **true** to include the context node in the selection; otherwise, **false**. |

### Return Value

An [XPathNodeIterator](../../xpathnodeiterator/) that contains the selected nodes.

## See Also

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)