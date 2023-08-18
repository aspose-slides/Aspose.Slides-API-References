---
title: ResolveFunction()
second_title: Aspose.Slides for C++ API Reference
description: When overridden in a derived class, resolves a function reference and returns an IXsltContextFunction representing the function. The IXsltContextFunction is used at execution time to get the return value of the function.
type: docs
weight: 27
url: /system.xml.xsl/xsltcontext/resolvefunction/
---
## XsltContext::ResolveFunction(String, String, ArrayPtr\<System::Xml::XPath::XPathResultType\>) method


When overridden in a derived class, resolves a function reference and returns an [IXsltContextFunction](../../ixsltcontextfunction/) representing the function. The [IXsltContextFunction](../../ixsltcontextfunction/) is used at execution time to get the return value of the function.

```cpp
virtual SharedPtr<IXsltContextFunction> System::Xml::Xsl::XsltContext::ResolveFunction(String prefix, String name, ArrayPtr<System::Xml::XPath::XPathResultType> ArgTypes)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | The prefix of the function as it appears in the [XPath](../../../system.xml.xpath/) expression. |
| name | [String](../../../system/string/) | The name of the function. |
| ArgTypes | [ArrayPtr](../../../system/arrayptr/)\<[System::Xml::XPath::XPathResultType](../../../system.xml.xpath/xpathresulttype/)\> | An array of argument types for the function being resolved. This allows you to select between methods with the same name (for example, overloaded methods). |

### Return Value

An [IXsltContextFunction](../../ixsltcontextfunction/) representing the function.

## See Also

* Enum [XPathResultType](../../../system.xml.xpath/xpathresulttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IXsltContextFunction](../../ixsltcontextfunction/)
* Class [String](../../../system/string/)
* Class [XsltContext](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)