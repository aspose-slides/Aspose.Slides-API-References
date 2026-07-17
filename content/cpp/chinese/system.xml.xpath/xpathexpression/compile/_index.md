---
title: Compile()
second_title: Aspose.Slides for C++ API 参考
description: 编译指定的 XPath 表达式并返回表示该 XPath 表达式的 XPathExpression 对象。
type: docs
weight: 66
url: /zh/system.xml.xpath/xpathexpression/compile/
---
## XPathExpression::Compile(const String\&) 方法


编译指定的 [XPath](../../) 表达式并返回表示 [XPath](../../) 表达式的 [XPathExpression](../) 对象。

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | 一个 [XPath](../../) 表达式。 |

### 返回值

一个 [XPathExpression](../) 对象。

## XPathExpression::Compile(const String\&, const SharedPtr\<IXmlNamespaceResolver\>\&) 方法


编译指定的 [XPath](../../) 表达式，使用用于命名空间解析的 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 对象，并返回表示 [XPath](../../) 表达式的 [XPathExpression](../) 对象。

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath, const SharedPtr<IXmlNamespaceResolver> &nsResolver)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | 一个 [XPath](../../) 表达式。 |
| nsResolver | const [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>\& | 一个实现用于命名空间解析的 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 接口的对象。 |

### 返回值

一个 [XPathExpression](../) 对象。

## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [XPathExpression](../)
* 类 [String](../../../system/string/)
* 类 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* 命名空间 [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)