---
title: SelectAncestors()
second_title: Aspose.Slides for C++ API Reference
description: Selects all the ancestor nodes of the current node that have a matching XPathNodeType.
type: docs
weight: 846
url: /system.xml.xpath/xpathnavigator/selectancestors/
---
## XPathNavigator::SelectAncestors(XPathNodeType, bool) method


Selects all the ancestor nodes of the current node that have a matching XPathNodeType.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(XPathNodeType type, bool matchSelf)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | The XPathNodeType of the ancestor nodes. |
| matchSelf | **bool** | To include the context node in the selection, **true**; otherwise, **false**. |

### Return Value

An [XPathNodeIterator](../../xpathnodeiterator/) that contains the selected nodes. The returned nodes are in reverse document order.

## XPathNavigator::SelectAncestors(String, String, bool) method


Selects all the ancestor nodes of the current node that have the specified local name and namespace URI.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(String name, String namespaceURI, bool matchSelf)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | The local name of the ancestor nodes. |
| namespaceURI | [String](../../../system/string/) | The namespace URI of the ancestor nodes. |
| matchSelf | **bool** | To include the context node in the selection, **true**; otherwise, **false**. |

### Return Value

An [XPathNodeIterator](../../xpathnodeiterator/) that contains the selected nodes. The returned nodes are in reverse document order.

## See Also

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)