---
title: SelectAncestors()
second_title: Aspose.Slides for C++ API Reference
description: Selects all the ancestor nodes of the current node that have a matching XPathNodeType.
type: docs
weight: 846
url: /cpp/system.xml.xpath/xpathnavigator/selectancestors/
---
## XPathNavigator::SelectAncestors([XPathNodeType](../../xpathnodetype/), **bool**) method


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

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Enum [XPathNodeType](../../xpathnodetype/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)
## XPathNavigator::SelectAncestors([String](../../../system/string/), [String](../../../system/string/), **bool**) method


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

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)
