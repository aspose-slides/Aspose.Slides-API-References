---
title: MoveToFirst()
second_title: Aspose.Slides for C++ API Reference
description: Moves the XPathNavigator to the first sibling node of the current node.
type: docs
weight: 612
url: /system.xml.xpath/xpathnavigator/movetofirst/
---
## XPathNavigator::MoveToFirst() method


Moves the [XPathNavigator](../) to the first sibling node of the current node.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFirst()
```


### Return Value

**true** if the [XPathNavigator](../) is successful moving to the first sibling node of the current node; **false** if there is no first sibling, or if the [XPathNavigator](../) is currently positioned on an attribute node. If the [XPathNavigator](../) is already positioned on the first sibling, [XPathNavigator](../) will return **true** and will not move its position. If [XPathNavigator::MoveToFirst](./) returns **false** because there is no first sibling, or if [XPathNavigator](../) is currently positioned on an attribute, the position of the [XPathNavigator](../) is unchanged.

## See Also

* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)