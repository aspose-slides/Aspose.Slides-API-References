---
title: Compile()
second_title: Aspose.Slides for C++ API Reference
description: Compiles the XPath expression specified and returns an XPathExpression object representing the XPath expression.
type: docs
weight: 66
url: /system.xml.xpath/xpathexpression/compile/
---
## XPathExpression::Compile(const String\&) method


Compiles the [XPath](../../) expression specified and returns an [XPathExpression](../) object representing the [XPath](../../) expression.

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | An [XPath](../../) expression. |

### Return Value

An [XPathExpression](../) object.

## XPathExpression::Compile(const String\&, const SharedPtr\<IXmlNamespaceResolver\>\&) method


Compiles the specified [XPath](../../) expression, with the [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object specified for namespace resolution, and returns an [XPathExpression](../) object that represents the [XPath](../../) expression.

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath, const SharedPtr<IXmlNamespaceResolver> &nsResolver)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | An [XPath](../../) expression. |
| nsResolver | const [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>\& | An object that implements the [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) interface for namespace resolution. |

### Return Value

An [XPathExpression](../) object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathExpression](../)
* Class [String](../../../system/string/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)