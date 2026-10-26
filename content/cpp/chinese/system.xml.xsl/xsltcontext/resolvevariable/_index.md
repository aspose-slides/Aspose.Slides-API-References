---
title: ResolveVariable()
second_title: Aspose.Slides C++ API 参考
description: 在派生类中重写时，解析变量引用并返回表示该变量的 IXsltContextVariable。
type: docs
weight: 14
url: /zh/system.xml.xsl/xsltcontext/resolvevariable/
---
## XsltContext::ResolveVariable(String, String) 方法

当在派生类中重写时，解析变量引用并返回一个 [IXsltContextVariable](../../ixsltcontextvariable/)，该对象表示该变量。

```cpp
virtual SharedPtr<IXsltContextVariable> System::Xml::Xsl::XsltContext::ResolveVariable(String prefix, String name)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | 变量的前缀，在 [XPath](../../../system.xml.xpath/) 表达式中出现的形式。 |
| name | [String](../../../system/string/) | 变量的名称。 |

### 返回值

一个 [IXsltContextVariable](../../ixsltcontextvariable/)，在运行时表示该变量。

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IXsltContextVariable](../../ixsltcontextvariable/)
* 类 [String](../../../system/string/)
* 类 [XsltContext](../)
* 命名空间 [System::Xml::Xsl](../../)
* 库 [Aspose.Slides](../../../)