---
title: PreserveWhitespace()
second_title: Aspose.Slides for C++ API 参考
description: 当在派生类中重写时，评估是否在给定上下文中保留空白节点或剥除它们。
type: docs
weight: 40
url: /zh/system.xml.xsl/xsltcontext/preservewhitespace/
---
## XsltContext::PreserveWhitespace(SharedPtr\<System::Xml::XPath::XPathNavigator\>) 方法

当在派生类中重写时，评估是否在给定上下文中保留空白节点或剥离它们。

```cpp
virtual bool System::Xml::Xsl::XsltContext::PreserveWhitespace(SharedPtr<System::Xml::XPath::XPathNavigator> node)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | 当前上下文中要保留或剥离的空白节点。 |

### 返回值

如果要保留空白则为 **true**；如果要剥离空白则为 **false**。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* 类 [XsltContext](../)
* 命名空间 [System::Xml::Xsl](../../)
* 库 [Aspose.Slides](../../../)