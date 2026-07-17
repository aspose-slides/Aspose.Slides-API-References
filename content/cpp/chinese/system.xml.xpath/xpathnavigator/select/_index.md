---
title: Select()
second_title: Aspose.Slides for C++ API 参考
description: 使用指定的 XPath 表达式选择节点集。
type: docs
weight: 794
url: /zh/system.xml.xpath/xpathnavigator/select/
---
## XPathNavigator::Select(String) 方法

使用指定的 [XPath](../../) 表达式选择节点集。

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | [String](../../../system/string/) 表示 [XPath](../../) 表达式。 |

### 返回值

指向所选节点集的 [XPathNodeIterator](../../xpathnodeiterator/)。

## XPathNavigator::Select(String, SharedPtr\<IXmlNamespaceResolver\>) 方法

使用指定的 [XPath](../../) 表达式并使用指定的 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 对象解析命名空间前缀来选择节点集。

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | [String](../../../system/string/) 表示 [XPath](../../) 表达式。 |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | 用于解析命名空间前缀的 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 对象。 |

### 返回值

指向所选节点集的 [XPathNodeIterator](../../xpathnodeiterator/)。

## XPathNavigator::Select(SharedPtr\<XPathExpression\>) 方法

使用指定的 [XPathExpression](../../xpathexpression/) 选择节点集。

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(SharedPtr<XPathExpression> expr)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | 包含已编译的 [XPath](../../) 查询的 [XPathExpression](../../xpathexpression/) 对象。 |

### 返回值

指向所选节点集的 [XPathNodeIterator](../../xpathnodeiterator/)。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XPathNodeIterator](../../xpathnodeiterator/)
* 类 [String](../../../system/string/)
* 类 [XPathNavigator](../)
* 类 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* 类 [XPathExpression](../../xpathexpression/)
* 命名空间 [System::Xml::XPath](../../)
* 库 [Aspose.Slides](../../../)