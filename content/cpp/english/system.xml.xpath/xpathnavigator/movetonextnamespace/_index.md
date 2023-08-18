---
title: MoveToNextNamespace()
second_title: Aspose.Slides for C++ API Reference
description: When overridden in a derived class, moves the XPathNavigator to the next namespace node matching the XPathNamespaceScope specified.
type: docs
weight: 573
url: /system.xml.xpath/xpathnavigator/movetonextnamespace/
---
## XPathNavigator::MoveToNextNamespace(XPathNamespaceScope) method


When overridden in a derived class, moves the [XPathNavigator](../) to the next namespace node matching the XPathNamespaceScope specified.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNextNamespace(XPathNamespaceScope namespaceScope)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| namespaceScope | [XPathNamespaceScope](../../xpathnamespacescope/) | An XPathNamespaceScope value describing the namespace scope. |

### Return Value

**true** if the [XPathNavigator](../) is successful moving to the next namespace node; otherwise, **false**. If **false**, the position of the [XPathNavigator](../) is unchanged.

## XPathNavigator::MoveToNextNamespace() method


Moves the [XPathNavigator](../) to the next namespace node.

```cpp
bool System::Xml::XPath::XPathNavigator::MoveToNextNamespace()
```


### Return Value

**true** if the [XPathNavigator](../) is successful moving to the next namespace node; otherwise, **false**. If **false**, the position of the [XPathNavigator](../) is unchanged.

## See Also

* Enum [XPathNamespaceScope](../../xpathnamespacescope/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)