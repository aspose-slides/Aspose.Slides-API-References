---
title: MoveToChild()
second_title: Aspose.Slides for C++ API Reference
description: Moves the XPathNavigator to the child node with the local name and namespace URI specified.
type: docs
weight: 690
url: /system.xml.xpath/xpathnavigator/movetochild/
---
## XPathNavigator::MoveToChild(String, String) method


Moves the [XPathNavigator](../) to the child node with the local name and namespace URI specified.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(String localName, String namespaceURI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | The local name of the child node to move to. |
| namespaceURI | [String](../../../system/string/) | The namespace URI of the child node to move to. |

### Return Value

**true** if the [XPathNavigator](../) is successful moving to the child node; otherwise, **false**. If **false**, the position of the [XPathNavigator](../) is unchanged.

## XPathNavigator::MoveToChild(XPathNodeType) method


Moves the [XPathNavigator](../) to the child node of the XPathNodeType specified.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(XPathNodeType type)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | The XPathNodeType of the child node to move to. |

### Return Value

**true** if the [XPathNavigator](../) is successful moving to the child node; otherwise, **false**. If **false**, the position of the [XPathNavigator](../) is unchanged.

## See Also

* Enum [XPathNodeType](../../xpathnodetype/)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)