---
title: Invoke()
second_title: Aspose.Slides for C++ API 参考
description: 提供在给定上下文中使用给定参数调用函数的方法。
type: docs
weight: 53
url: /zh/system.xml.xsl/ixsltcontextfunction/invoke/
---
## IXsltContextFunction::Invoke(SharedPtr\<XsltContext\>, ArrayPtr\<SharedPtr\<Object\>\>, SharedPtr\<System::Xml::XPath::XPathNavigator\>) 方法

提供在给定上下文中使用给定参数调用函数的方法。

```cpp
virtual SharedPtr<Object> System::Xml::Xsl::IXsltContextFunction::Invoke(SharedPtr<XsltContext> xsltContext, ArrayPtr<SharedPtr<Object>> args, SharedPtr<System::Xml::XPath::XPathNavigator> docContext)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xsltContext | [SharedPtr](../../../system/sharedptr/)\<[XsltContext](../../xsltcontext/)\> | 函数调用的 XSLT 上下文。 |
| args | [ArrayPtr](../../../system/arrayptr/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | 函数调用的参数。每个参数是数组中的一个元素。 |
| docContext | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | 函数调用的上下文节点。 |

### 返回值

一个表示函数返回值的 [Object](../../../system/object/)。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [Object](../../../system/object/)
* 类 [XsltContext](../../xsltcontext/)
* 类 [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* 类 [IXsltContextFunction](../)
* 命名空间 [System::Xml::Xsl](../../)
* 库 [Aspose.Slides](../../../)