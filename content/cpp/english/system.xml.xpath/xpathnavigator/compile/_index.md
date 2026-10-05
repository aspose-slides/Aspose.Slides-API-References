---
title: Compile()
second_title: Aspose.Slides for C++ API Reference
description: Compiles a string representing an XPath expression and returns an XPathExpression object.
type: docs
weight: 768
url: /system.xml.xpath/xpathnavigator/compile/
---
## XPathNavigator::Compile(String) method


Compiles a string representing an [XPath](../../) expression and returns an [XPathExpression](../../xpathexpression/) object.

```cpp
virtual SharedPtr<XPathExpression> System::Xml::XPath::XPathNavigator::Compile(String xpath)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | A string representing an [XPath](../../) expression. |

### Return Value

An [XPathExpression](../../xpathexpression/) object representing the [XPath](../../) expression.

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentException | The **xpath** parameter contains an [XPath](../../) expression that is not valid. |
| XPathException | The [XPath](../../) expression is not valid. |


## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathExpression](../../xpathexpression/)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)