---
title: SetValue()
second_title: Aspose.Slides for C++ API Reference
description: Sets the value of the current node.
type: docs
weight: 352
url: /system.xml.xpath/xpathnavigator/setvalue/
---
## XPathNavigator::SetValue(String) method


Sets the value of the current node.

```cpp
virtual void System::Xml::XPath::XPathNavigator::SetValue(String value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | [String](../../../system/string/) | The new value of the node. |

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentNullException | The value parameter is **nullptr**. |
| InvalidOperationException | The [XPathNavigator](../) is positioned on the root node, a namespace node, or the specified value is invalid. |
| NotSupportedException | The [XPathNavigator](../) does not support editing. |


## See Also

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)