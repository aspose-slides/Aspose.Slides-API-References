---
title: ResolveFunction()
second_title: Aspose.Slides for C++ API 参考
description: 当在派生类中被重写时，解析函数引用并返回一个表示该函数的 IXsltContextFunction。IXsltContextFunction 在执行时用于获取函数的返回值。
type: docs
weight: 27
url: /zh/system.xml.xsl/xsltcontext/resolvefunction/
---
## XsltContext::ResolveFunction(String, String, ArrayPtr\<System::Xml::XPath::XPathResultType\>) 方法

当在派生类中被重写时，解析函数引用并返回一个 [IXsltContextFunction](../../ixsltcontextfunction/)，该对象表示该函数。[IXsltContextFunction](../../ixsltcontextfunction/) 在执行时用于获取函数的返回值。

```cpp
virtual SharedPtr<IXsltContextFunction> System::Xml::Xsl::XsltContext::ResolveFunction(String prefix, String name, ArrayPtr<System::Xml::XPath::XPathResultType> ArgTypes)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | 函数在 [XPath](../../../system.xml.xpath/) 表达式中出现的前缀。 |
| name | [String](../../../system/string/) | 函数的名称。 |
| ArgTypes | [ArrayPtr](../../../system/arrayptr/)\<[System::Xml::XPath::XPathResultType](../../../system.xml.xpath/xpathresulttype/)\> | 被解析函数的参数类型数组。这使您可以在同名方法之间进行选择（例如，重载方法）。 |

### 返回值

一个表示该函数的 [IXsltContextFunction](../../ixsltcontextfunction/)。

## 另请参见

* Enum [XPathResultType](../../../system.xml.xpath/xpathresulttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IXsltContextFunction](../../ixsltcontextfunction/)
* Class [String](../../../system/string/)
* Class [XsltContext](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)