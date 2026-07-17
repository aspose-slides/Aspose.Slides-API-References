---
title: CompareDocument()
second_title: Aspose.Slides for C++ API 参考
description: 当在派生类中重写时，根据文档被 XSLT 处理器加载的顺序（即 XslTransform 类），比较两个文档的基础统一资源标识符 (URI)。
type: docs
weight: 53
url: /zh/system.xml.xsl/xsltcontext/comparedocument/
---
## XsltContext::CompareDocument(String, String) 方法

当在派生类中重写时，比较两个文档的基础统一资源标识符 (URI)，依据文档被 XSLT 处理器加载的顺序（即 [XslTransform](../../xsltransform/) 类）。

```cpp
virtual int32_t System::Xml::Xsl::XsltContext::CompareDocument(String baseUri, String nextbaseUri)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| baseUri | [String](../../../system/string/) | 要比较的第一个文档的基础 URI。 |
| nextbaseUri | [String](../../../system/string/) | 要比较的第二个文档的基础 URI。 |

### 返回值

一个整数值，描述两个基础 URI 的相对顺序：-1 表示 **baseUri** 在 **nextbaseUri** 之前；0 表示两个基础 URI 相同；1 表示 **baseUri** 在 **nextbaseUri** 之后。

## 另请参见

* 类 [String](../../../system/string/)
* 类 [XsltContext](../)
* 命名空间 [System::Xml::Xsl](../../)
* 库 [Aspose.Slides](../../../)