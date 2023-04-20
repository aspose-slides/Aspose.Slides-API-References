---
title: MoveToFirstNamespace()
second_title: Aspose.Slides for C++ API Reference
description: When overridden in a derived class, moves the XPathNavigator to the first namespace node that matches the XPathNamespaceScope specified.
type: docs
weight: 560
url: /cpp/system.xml.xpath/xpathnavigator/movetofirstnamespace/
---
## XPathNavigator::MoveToFirstNamespace(XPathNamespaceScope) method


When overridden in a derived class, moves the [XPathNavigator](../) to the first namespace node that matches the XPathNamespaceScope specified.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFirstNamespace(XPathNamespaceScope namespaceScope)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| namespaceScope | [XPathNamespaceScope](../../xpathnamespacescope/) | An XPathNamespaceScope value describing the namespace scope. |

### Return Value

**true** if the [XPathNavigator](../) is successful moving to the first namespace node; otherwise, **false**. If **false**, the position of the [XPathNavigator](../) is unchanged.

## XPathNavigator::MoveToFirstNamespace() method


Moves the [XPathNavigator](../) to first namespace node of the current node.

```cpp
bool System::Xml::XPath::XPathNavigator::MoveToFirstNamespace()
```


### Return Value

**true** if the [XPathNavigator](../) is successful moving to the first namespace node; otherwise, **false**. If **false**, the position of the [XPathNavigator](../) is unchanged.

## See Also

* Enum [XPathNamespaceScope](../../xpathnamespacescope/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)