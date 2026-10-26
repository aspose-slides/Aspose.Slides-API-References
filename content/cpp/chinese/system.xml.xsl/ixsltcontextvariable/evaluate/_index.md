---
title: Evaluate()
second_title: Aspose.Slides C++ API 参考
description: 在运行时求值变量并返回表示该变量值的对象。
type: docs
weight: 40
url: /zh/system.xml.xsl/ixsltcontextvariable/evaluate/
---
## IXsltContextVariable::Evaluate(SharedPtr\<XsltContext\>) 方法

在运行时求值变量并返回表示该变量值的对象。

```cpp
virtual SharedPtr<Object> System::Xml::Xsl::IXsltContextVariable::Evaluate(SharedPtr<XsltContext> xsltContext)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xsltContext | [SharedPtr](../../../system/sharedptr/)\<[XsltContext](../../xsltcontext/)\> | [XsltContext](../../xsltcontext/)，表示变量的执行上下文。 |

### 返回值

[Object](../../../system/object/)，表示变量的值。可能的返回类型包括 number、string、[Boolean](../../../system/boolean/)、文档片段或节点集。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Object](../../../system/object/)
* 类 [XsltContext](../../xsltcontext/)
* 类 [IXsltContextVariable](../)
* 命名空间 [System::Xml::Xsl](../../)
* 库 [Aspose.Slides](../../../)