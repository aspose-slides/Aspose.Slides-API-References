---
title: SelectSingleNode()
second_title: Aspose.Slides for C++ API 参考
description: 使用指定的 XPath 查询，在 XPathNavigator 中选择单个节点。
type: docs
weight: 781
url: /zh/system.xml.xpath/xpathnavigator/selectsinglenode/
---
## XPathNavigator::SelectSingleNode(String) 方法

使用指定的[XPath](../../)查询，在[XPathNavigator](../)中选择单个节点。

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | 表示 [XPath](../../) 表达式的 [String](../../../system/string/)。 |

### 返回值

包含指定的[XPath](../../)查询的第一个匹配节点的[XPathNavigator](../)对象；如果没有查询结果，则为 **nullptr**。

## XPathNavigator::SelectSingleNode(String, SharedPtr\<IXmlNamespaceResolver\>) 方法

使用指定的[XPath](../../)查询，并使用指定的[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)对象解析命名空间前缀，在[XPathNavigator](../)对象中选择单个节点。

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | 表示 [XPath](../../) 表达式的 [String](../../../system/string/)。 |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | 用于在[XPath](../../)查询中解析命名空间前缀的[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)对象。 |

### 返回值

包含指定的[XPath](../../)查询的第一个匹配节点的[XPathNavigator](../)对象；如果没有查询结果，则为 **nullptr**。

## XPathNavigator::SelectSingleNode(SharedPtr\<XPathExpression\>) 方法

使用指定的[XPathExpression](../../xpathexpression/)对象，在[XPathNavigator](../)中选择单个节点。

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(SharedPtr<XPathExpression> expression)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| expression | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | 包含已编译的[XPath](../../)查询的[XPathExpression](../../xpathexpression/)对象。 |

### 返回值

包含指定的[XPath](../../)查询的第一个匹配节点的[XPathNavigator](../)对象；如果没有查询结果，则为 **nullptr**。

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [XPathNavigator](../)
* 类 [String](../../../system/string/)
* 类 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* 类 [XPathExpression](../../xpathexpression/)
* 命名空间 [System::Xml::XPath](../../)
* 库 [Aspose.Slides](../../../)