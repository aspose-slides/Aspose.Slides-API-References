---
title: GetAttribute()
second_title: Aspose.Slides for C++ API Reference
description: Returns the value of the attribute with the specified local name and namespace URI.
type: docs
weight: 482
url: /cpp/system.xml.xpath/xpathnavigator/getattribute/
---
## XPathNavigator::GetAttribute(String, String) method


Returns the value of the attribute with the specified local name and namespace URI.

```cpp
virtual String System::Xml::XPath::XPathNavigator::GetAttribute(String localName, String namespaceURI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | The local name of the attribute. **localName** is case-sensitive. |
| namespaceURI | [String](../../../system/string/) | The namespace URI of the attribute. |

### Return Value

A [String](../../../system/string/) that contains the value of the specified attribute; [String::Empty](../../../system/string/empty/) if a matching attribute is not found, or if the [XPathNavigator](../) is not positioned on an element node.

## See Also

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)