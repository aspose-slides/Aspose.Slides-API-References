---
title: PrependChild()
second_title: Aspose.Slides for C++ API 参考
description: 返回一个 XmlWriter 对象，用于在当前节点的子节点列表开头创建一个新的子节点。
type: docs
weight: 872
url: /zh/system.xml.xpath/xpathnavigator/prependchild/
---
## XPathNavigator::PrependChild() 方法

返回一个 [XmlWriter](../../../system.xml/xmlwriter/) 对象，用于在当前节点的子节点列表开头创建一个新的子节点。

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::PrependChild()
```

### 返回值

一个 [XmlWriter](../../../system.xml/xmlwriter/) 对象，用于在当前节点的子节点列表开头创建一个新的子节点。

## XPathNavigator::PrependChild(String) 方法

使用指定的 XML 字符串，在当前节点的子节点列表开头创建一个新的子节点。

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(String newChild)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newChild | [String](../../../system/string/) | 新子节点的 XML 数据字符串。 |

## XPathNavigator::PrependChild(SharedPtr\<XmlReader\>) 方法

使用指定的 [XmlReader](../../../system.xml/xmlreader/) 对象的 XML 内容，在当前节点的子节点列表开头创建一个新的子节点。

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(SharedPtr<XmlReader> newChild)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | 一个定位在新子节点 XML 数据上的 [XmlReader](../../../system.xml/xmlreader/) 对象。 |

## XPathNavigator::PrependChild(SharedPtr\<XPathNavigator\>) 方法

使用指定的 [XPathNavigator](../) 对象中的节点，在当前节点的子节点列表开头创建一个新的子节点。

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(SharedPtr<XPathNavigator> newChild)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | 一个定位在要添加为新子节点的节点上的 [XPathNavigator](../) 对象。 |

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlWriter](../../../system.xml/xmlwriter/)
* 类 [XPathNavigator](../)
* 类 [String](../../../system/string/)
* 类 [XmlReader](../../../system.xml/xmlreader/)
* 命名空间 [System::Xml::XPath](../../)
* 库 [Aspose.Slides](../../../)