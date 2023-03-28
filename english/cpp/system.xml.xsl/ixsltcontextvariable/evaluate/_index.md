---
title: Evaluate()
second_title: Aspose.Slides for C++ API Reference
description: Evaluates the variable at runtime and returns an object that represents the value of the variable.
type: docs
weight: 40
url: /cpp/system.xml.xsl/ixsltcontextvariable/evaluate/
---
## IXsltContextVariable::Evaluate([SharedPtr](../../../system/sharedptr/)\<[XsltContext](../../xsltcontext/)\>) method


Evaluates the variable at runtime and returns an object that represents the value of the variable.

```cpp
virtual SharedPtr<Object> System::Xml::Xsl::IXsltContextVariable::Evaluate(SharedPtr<XsltContext> xsltContext)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| xsltContext | [SharedPtr](../../../system/sharedptr/)\<[XsltContext](../../xsltcontext/)\> | An [XsltContext](../../xsltcontext/) representing the execution context of the variable. |

### Return Value

An [Object](../../../system/object/) representing the value of the variable. Possible return types include number, string, [Boolean](../../../system/boolean/), document fragment, or node set.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [XsltContext](../../xsltcontext/)
* Class [IXsltContextVariable](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)
