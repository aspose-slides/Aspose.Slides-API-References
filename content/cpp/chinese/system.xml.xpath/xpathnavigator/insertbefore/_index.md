---
title: InsertBefore()
second_title: Aspose.Slides for C++ API 参考文档
description: 返回一个 XmlWriter 对象，用于在当前选定的节点之前创建一个新的同级节点。
type: docs
weight: 911
url: /zh/system.xml.xpath/xpathnavigator/insertbefore/
---
## XPathNavigator::InsertBefore() 方法


返回一个 [XmlWriter](../../../system.xml/xmlwriter/) 对象，用于在当前选定的节点之前创建一个新的同级节点。

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertBefore()
```


### 返回值

一个 [XmlWriter](../../../system.xml/xmlwriter/) 对象，用于在当前选定的节点之前创建一个新的同级节点。

## XPathNavigator::InsertBefore(String) 方法


使用指定的 XML 字符串，在当前选定的节点之前创建一个新的同级节点。

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(String newSibling)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newSibling | [String](../../../system/string/) | 新同级节点的 XML 数据字符串。 |

## XPathNavigator::InsertBefore(SharedPtr\<XmlReader\>) 方法


使用指定的 [XmlReader](../../../system.xml/xmlreader/) 对象的 XML 内容，在当前选定的节点之前创建一个新的同级节点。

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XmlReader> newSibling)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | 一个定位在新同级节点 XML 数据上的 [XmlReader](../../../system.xml/xmlreader/) 对象。 |

## XPathNavigator::InsertBefore(SharedPtr\<XPathNavigator\>) 方法


使用指定的 [XPathNavigator](../) 中的节点，在当前选定的节点之前创建一个新的同级节点。

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XPathNavigator> newSibling)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | 一个定位在要添加为新同级节点的节点上的 [XPathNavigator](../) 对象。 |

## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [XmlWriter](../../../system.xml/xmlwriter/)
* 类 [XPathNavigator](../)
* 类 [String](../../../system/string/)
* 类 [XmlReader](../../../system.xml/xmlreader/)
* 命名空间 [System::Xml::XPath](../../)
* 库 [Aspose.Slides](../../../)