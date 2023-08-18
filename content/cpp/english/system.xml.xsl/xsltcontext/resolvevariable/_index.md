---
title: ResolveVariable()
second_title: Aspose.Slides for C++ API Reference
description: When overridden in a derived class, resolves a variable reference and returns an IXsltContextVariable representing the variable.
type: docs
weight: 14
url: /system.xml.xsl/xsltcontext/resolvevariable/
---
## XsltContext::ResolveVariable(String, String) method


When overridden in a derived class, resolves a variable reference and returns an [IXsltContextVariable](../../ixsltcontextvariable/) representing the variable.

```cpp
virtual SharedPtr<IXsltContextVariable> System::Xml::Xsl::XsltContext::ResolveVariable(String prefix, String name)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | The prefix of the variable as it appears in the [XPath](../../../system.xml.xpath/) expression. |
| name | [String](../../../system/string/) | The name of the variable. |

### Return Value

An [IXsltContextVariable](../../ixsltcontextvariable/) representing the variable at runtime.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXsltContextVariable](../../ixsltcontextvariable/)
* Class [String](../../../system/string/)
* Class [XsltContext](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)