---
title: InsertAfter()
second_title: Aspose.Slides C++ API 参考
description: 返回一个用于在当前选定节点之后创建新兄弟节点的 XmlWriter 对象。
type: docs
weight: 898
url: /zh/system.xml.xpath/xpathnavigator/insertafter/
---
## XPathNavigator::InsertAfter() 方法

返回一个用于在当前选定节点之后创建新兄弟节点的 [XmlWriter](../../../system.xml/xmlwriter/) 对象。

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertAfter()
```

### 返回值

一个用于在当前选定节点之后创建新兄弟节点的 [XmlWriter](../../../system.xml/xmlwriter/) 对象。

## XPathNavigator::InsertAfter(String) 方法

使用指定的 XML 字符串在当前选定节点之后创建一个新兄弟节点。

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(String newSibling)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newSibling | [String](../../../system/string/) | 新兄弟节点的 XML 数据字符串。 |

## XPathNavigator::InsertAfter(SharedPtr\<XmlReader\>) 方法

使用指定的 [XmlReader](../../../system.xml/xmlreader/) 对象的 XML 内容在当前选定节点之后创建一个新兄弟节点。

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(SharedPtr<XmlReader> newSibling)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | 一个定位在新兄弟节点 XML 数据上的 [XmlReader](../../../system.xml/xmlreader/) 对象。 |

## XPathNavigator::InsertAfter(SharedPtr\<XPathNavigator\>) 方法

使用指定的 [XPathNavigator](../) 对象中的节点在当前选定节点之后创建一个新兄弟节点。

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(SharedPtr<XPathNavigator> newSibling)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | 一个定位在要添加为新兄弟节点的节点上的 [XPathNavigator](../) 对象。 |

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)