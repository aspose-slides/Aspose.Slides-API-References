---
title: LookupNamespace()
second_title: Aspose.Slides for C++ API Reference
description: Returns the namespace URI for the specified prefix.
type: docs
weight: 404
url: /cpp/system.xml.xpath/xpathnavigator/lookupnamespace/
---
## XPathNavigator::LookupNamespace(const [String](../../../system/string/)\&) method


Returns the namespace URI for the specified prefix.

```cpp
String System::Xml::XPath::XPathNavigator::LookupNamespace(const String &prefix) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | The prefix whose namespace URI you want to resolve. To match the default namespace, pass [String::Empty](../../../system/string/empty/). |

### Return Value

A [String](../../../system/string/) that contains the namespace URI assigned to the namespace prefix specified; **nullptr** if no namespace URI is assigned to the prefix specified. The [String](../../../system/string/) returned is atomized.

## See Also

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)
