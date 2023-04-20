---
title: SelectChildren()
second_title: Aspose.Slides for C++ API Reference
description: Selects all the child nodes of the current node that have the matching XPathNodeType.
type: docs
weight: 833
url: /cpp/system.xml.xpath/xpathnavigator/selectchildren/
---
## XPathNavigator::SelectChildren(XPathNodeType) method


Selects all the child nodes of the current node that have the matching XPathNodeType.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(XPathNodeType type)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | The XPathNodeType of the child nodes. |

### Return Value

An [XPathNodeIterator](../../xpathnodeiterator/) that contains the selected nodes.

## XPathNavigator::SelectChildren(String, String) method


Selects all the child nodes of the current node that have the local name and namespace URI specified.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectChildren(String name, String namespaceURI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | The local name of the child nodes. |
| namespaceURI | [String](../../../system/string/) | The namespace URI of the child nodes. |

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