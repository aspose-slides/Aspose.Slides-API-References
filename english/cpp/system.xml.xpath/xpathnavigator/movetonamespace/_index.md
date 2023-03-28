---
title: MoveToNamespace()
second_title: Aspose.Slides for C++ API Reference
description: Moves the XPathNavigator to the namespace node with the specified namespace prefix.
type: docs
weight: 547
url: /cpp/system.xml.xpath/xpathnavigator/movetonamespace/
---
## XPathNavigator::MoveToNamespace([String](../../../system/string/)) method


Moves the [XPathNavigator](../) to the namespace node with the specified namespace prefix.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNamespace(String name)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | The namespace prefix of the namespace node. |

### Return Value

**true** if the [XPathNavigator](../) is successful moving to the specified namespace; **false** if a matching namespace node was not found, or if the [XPathNavigator](../) is not positioned on an element node. If **false**, the position of the [XPathNavigator](../) is unchanged.

## See Also

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)
