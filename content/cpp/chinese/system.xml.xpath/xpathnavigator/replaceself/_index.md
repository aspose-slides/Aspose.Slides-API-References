---
title: ReplaceSelf()
second_title: Aspose.Slides for C++ API 参考
description: 用指定字符串的内容替换当前节点。
type: docs
weight: 950
url: /zh/system.xml.xpath/xpathnavigator/replaceself/
---
## XPathNavigator::ReplaceSelf(String) 方法


用指定字符串的内容替换当前节点。

```cpp
virtual void System::Xml::XPath::XPathNavigator::ReplaceSelf(String newNode)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newNode | [String](../../../system/string/) | 用于新节点的 XML 数据字符串。 |

## XPathNavigator::ReplaceSelf(SharedPtr\<XmlReader\>) 方法


用指定的 [XmlReader](../../../system.xml/xmlreader/) 对象的内容替换当前节点。

```cpp
virtual void System::Xml::XPath::XPathNavigator::ReplaceSelf(SharedPtr<XmlReader> newNode)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newNode | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | 定位在新节点 XML 数据上的 [XmlReader](../../../system.xml/xmlreader/) 对象。 |

## XPathNavigator::ReplaceSelf(SharedPtr\<XPathNavigator\>) 方法


用指定的 [XPathNavigator](../) 对象的内容替换当前节点。

```cpp
virtual void System::Xml::XPath::XPathNavigator::ReplaceSelf(SharedPtr<XPathNavigator> newNode)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newNode | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | 定位在新节点上的 [XPathNavigator](../) 对象。 |

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [XPathNavigator](../)
* 类 [XmlReader](../../../system.xml/xmlreader/)
* 命名空间 [System::Xml::XPath](../../)
* 库 [Aspose.Slides](../../../)