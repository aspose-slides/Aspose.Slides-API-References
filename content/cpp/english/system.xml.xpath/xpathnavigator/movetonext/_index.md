---
title: MoveToNext()
second_title: Aspose.Slides for C++ API Reference
description: When overridden in a derived class, moves the XPathNavigator to the next sibling node of the current node.
type: docs
weight: 586
url: /system.xml.xpath/xpathnavigator/movetonext/
---
## XPathNavigator::MoveToNext() method


When overridden in a derived class, moves the [XPathNavigator](../) to the next sibling node of the current node.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext()=0
```


### Return Value

**true** if the [XPathNavigator](../) is successful moving to the next sibling node; otherwise **false** if there are no more siblings or if the [XPathNavigator](../) is currently positioned on an attribute node. If **false**, the position of the [XPathNavigator](../) is unchanged.

## XPathNavigator::MoveToNext(String, String) method


Moves the [XPathNavigator](../) to the next sibling node with the local name and namespace URI specified.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(String localName, String namespaceURI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | The local name of the next sibling node to move to. |
| namespaceURI | [String](../../../system/string/) | The namespace URI of the next sibling node to move to. |

### Return Value

**true** if the [XPathNavigator](../) is successful moving to the next sibling node; **false** if there are no more siblings, or if the [XPathNavigator](../) is currently positioned on an attribute node. If **false**, the position of the [XPathNavigator](../) is unchanged.

## XPathNavigator::MoveToNext(XPathNodeType) method


Moves the [XPathNavigator](../) to the next sibling node of the current node that matches the XPathNodeType specified.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(XPathNodeType type)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | The XPathNodeType of the sibling node to move to. |

### Return Value

**true** if the [XPathNavigator](../) is successful moving to the next sibling node; otherwise, **false** if there are no more siblings or if the [XPathNavigator](../) is currently positioned on an attribute node. If **false**, the position of the [XPathNavigator](../) is unchanged.

## See Also

* Enum [XPathNodeType](../../xpathnodetype/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)