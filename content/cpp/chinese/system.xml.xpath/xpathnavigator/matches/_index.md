---
title: Matches()
second_title: Aspose.Slides for C++ API 参考
description: 确定当前节点是否匹配指定的 XPathExpression。
type: docs
weight: 820
url: /zh/system.xml.xpath/xpathnavigator/matches/
---
## XPathNavigator::Matches(SharedPtr\<XPathExpression\>) 方法

确定当前节点是否匹配指定的 [XPathExpression](../../xpathexpression/)。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::Matches(SharedPtr<XPathExpression> expr)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | 一个包含已编译的 [XPath](../../) 表达式的 [XPathExpression](../../xpathexpression/) 对象。 |

### 返回值

**true** 如果当前节点匹配 [XPathExpression](../../xpathexpression/)；否则，**false**。

## XPathNavigator::Matches(String) 方法

确定当前节点是否匹配指定的 [XPath](../../) 表达式。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::Matches(String xpath)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | 该 [XPath](../../) 表达式。 |

### 返回值

**true** 如果当前节点匹配指定的 [XPath](../../) 表达式；否则，**false**。

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathExpression](../../xpathexpression/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)