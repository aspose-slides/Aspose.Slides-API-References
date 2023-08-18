---
title: PreserveWhitespace()
second_title: Aspose.Slides for C++ API Reference
description: When overridden in a derived class, evaluates whether to preserve white space nodes or strip them for the given context.
type: docs
weight: 40
url: /system.xml.xsl/xsltcontext/preservewhitespace/
---
## XsltContext::PreserveWhitespace(SharedPtr\<System::Xml::XPath::XPathNavigator\>) method


When overridden in a derived class, evaluates whether to preserve white space nodes or strip them for the given context.

```cpp
virtual bool System::Xml::Xsl::XsltContext::PreserveWhitespace(SharedPtr<System::Xml::XPath::XPathNavigator> node)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | The white space node that is to be preserved or stripped in the current context. |

### Return Value

**true** if the white space is to be preserved; **false** if the white space is to be stripped.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XsltContext](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)