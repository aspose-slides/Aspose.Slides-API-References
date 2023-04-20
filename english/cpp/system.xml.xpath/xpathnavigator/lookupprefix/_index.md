---
title: LookupPrefix()
second_title: Aspose.Slides for C++ API Reference
description: Returns the prefix declared for the specified namespace URI.
type: docs
weight: 417
url: /cpp/system.xml.xpath/xpathnavigator/lookupprefix/
---
## XPathNavigator::LookupPrefix(const String\&) method


Returns the prefix declared for the specified namespace URI.

```cpp
String System::Xml::XPath::XPathNavigator::LookupPrefix(const String &namespaceURI) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| namespaceURI | const [String](../../../system/string/)\& | The namespace URI to resolve for the prefix. |

### Return Value

A [String](../../../system/string/) that contains the namespace prefix assigned to the namespace URI specified; otherwise, [String::Empty](../../../system/string/empty/) if no prefix is assigned to the namespace URI specified. The [String](../../../system/string/) returned is atomized.

## See Also

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)