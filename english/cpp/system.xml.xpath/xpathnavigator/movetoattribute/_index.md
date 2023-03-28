---
title: MoveToAttribute()
second_title: Aspose.Slides for C++ API Reference
description: Moves the XPathNavigator to the attribute with the matching local name and namespace URI.
type: docs
weight: 495
url: /cpp/system.xml.xpath/xpathnavigator/movetoattribute/
---
## XPathNavigator::MoveToAttribute([String](../../../system/string/), [String](../../../system/string/)) method


Moves the [XPathNavigator](../) to the attribute with the matching local name and namespace URI.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToAttribute(String localName, String namespaceURI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | The local name of the attribute. |
| namespaceURI | [String](../../../system/string/) | The namespace URI of the attribute; **nullptr** for an empty namespace. |

### Return Value

**true** if the [XPathNavigator](../) is successful moving to the attribute; otherwise, **false**. If **false**, the position of the [XPathNavigator](../) is unchanged.

## See Also

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)
