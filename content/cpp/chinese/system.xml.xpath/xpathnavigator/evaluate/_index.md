---
title: Evaluate()
second_title: Aspose.Slides for C++ API 参考
description: 评估指定的 XPath 表达式并返回类型化的结果。
type: docs
weight: 807
url: /zh/system.xml.xpath/xpathnavigator/evaluate/
---
## XPathNavigator::Evaluate(String) 方法

评估指定的 [XPath](../../) 表达式并返回类型化的结果。

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | 表示可以评估的 [XPath](../../) 表达式的字符串。 |

### 返回值

表达式的结果 ([Boolean](../../../system/boolean/)、数字、字符串或节点集)。这分别映射到 [Boolean](../../../system/boolean/)、[Double](../../../system/double/)、[String](../../../system/string/) 或 [XPathNodeIterator](../../xpathnodeiterator/) 对象。

## XPathNavigator::Evaluate(String, SharedPtr\<IXmlNamespaceResolver\>) 方法

评估指定的 [XPath](../../) 表达式并返回类型化的结果，使用指定的 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 对象来解析 [XPath](../../) 表达式中的命名空间前缀。

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | 表示可以评估的 [XPath](../../) 表达式的字符串。 |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | 用于解析 [XPath](../../) 表达式中命名空间前缀的 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 对象。 |

### 返回值

表达式的结果 ([Boolean](../../../system/boolean/)、数字、字符串或节点集)。这分别映射到 [Boolean](../../../system/boolean/)、[Double](../../../system/double/)、[String](../../../system/string/) 或 [XPathNodeIterator](../../xpathnodeiterator/) 对象。

## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>) 方法

评估 [XPathExpression](../../xpathexpression/) 并返回类型化的结果。

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | 可以评估的 [XPathExpression](../../xpathexpression/)。 |

### 返回值

表达式的结果 ([Boolean](../../../system/boolean/)、数字、字符串或节点集)。这分别映射到 [Boolean](../../../system/boolean/)、[Double](../../../system/double/)、[String](../../../system/string/) 或 [XPathNodeIterator](../../xpathnodeiterator/) 对象。

## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>, SharedPtr\<XPathNodeIterator\>) 方法

使用提供的上下文评估 [XPathExpression](../../xpathexpression/)，并返回类型化的结果。

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr, SharedPtr<XPathNodeIterator> context)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | 可以评估的 [XPathExpression](../../xpathexpression/)。 |
| context | [SharedPtr](../../../system/sharedptr/)\<[XPathNodeIterator](../../xpathnodeiterator/)\> | 指向要在其上执行评估的选定节点集的 [XPathNodeIterator](../../xpathnodeiterator/)。 |

### 返回值

表达式的结果 ([Boolean](../../../system/boolean/)、数字、字符串或节点集)。这分别映射到 [Boolean](../../../system/boolean/)、[Double](../../../system/double/)、[String](../../../system/string/) 或 [XPathNodeIterator](../../xpathnodeiterator/) 对象。

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Object](../../../system/object/)
* 类 [String](../../../system/string/)
* 类 [XPathNavigator](../)
* 类 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* 类 [XPathExpression](../../xpathexpression/)
* 类 [XPathNodeIterator](../../xpathnodeiterator/)
* 命名空间 [System::Xml::XPath](../../)
* 库 [Aspose.Slides](../../../)