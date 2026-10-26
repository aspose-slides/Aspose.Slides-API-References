---
title: IsStartElement()
second_title: Aspose.Slides for C++ API 参考
description: "调用 XmlReader::MoveToContent 并测试当前内容节点是否为开始标签或空元素标签。"
type: docs
weight: 885
url: /zh/system.xml/xmlreader/isstartelement/
---
## XmlReader::IsStartElement() 方法


调用 [XmlReader::MoveToContent](../movetocontent/) 并测试当前内容节点是否为开始标签或空元素标签。

```cpp
virtual bool System::Xml::XmlReader::IsStartElement()
```


### 返回值

**true** 如果 [XmlReader::MoveToContent](../movetocontent/) 找到开始标签或空元素标签，则为 **true**；如果发现的节点类型不是 [XmlNodeType::Element](../../xmlnodetype/)，则为 **false**。

## XmlReader::IsStartElement(String) 方法


调用 [XmlReader::MoveToContent](../movetocontent/) 并测试当前内容节点是否为开始标签或空元素标签，以及找到的元素的 [XmlReader::get_Name](../get_name/) 值是否匹配给定的参数。

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String name)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 与找到的元素的 **Name** 值匹配的字符串。 |

### 返回值

**true** 如果结果节点是元素且 **Name** 值匹配指定的字符串，则为 **true**；如果发现的节点类型不是 [XmlNodeType::Element](../../xmlnodetype/)，或者元素的 **Name** 值与指定的字符串不匹配，则为 **false**。

## XmlReader::IsStartElement(String, String) 方法


调用 [XmlReader::MoveToContent](../movetocontent/) 并测试当前内容节点是否为开始标签或空元素标签，以及找到的元素的 [XmlReader::get_LocalName](../get_localname/) 和 [XmlReader::get_NamespaceURI](../get_namespaceuri/) 值是否匹配给定的字符串。

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String localname, String ns)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| localname | [String](../../../system/string/) | 用于匹配找到的元素的 **LocalName** 值的字符串。 |
| ns | [String](../../../system/string/) | 用于匹配找到的元素的 **NamespaceURI** 值的字符串。 |

### 返回值

**true** 如果结果节点是元素，则为 **true**；如果发现的节点类型不是 [XmlNodeType::Element](../../xmlnodetype/)，或者元素的 **LocalName** 和 **NamespaceURI** 值与指定的字符串不匹配，则为 **false**。

## 另请参阅

* 类 [XmlReader](../)
* 类 [String](../../../system/string/)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)