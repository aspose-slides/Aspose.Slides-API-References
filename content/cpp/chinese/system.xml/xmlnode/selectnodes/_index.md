---
title: SelectNodes()
second_title: Aspose.Slides C++ API 参考
description: 选择与 XPath 表达式匹配的节点列表。
type: docs
weight: 365
url: /zh/system.xml/xmlnode/selectnodes/
---
## XmlNode::SelectNodes(const String\&) 方法

选择匹配 [XPath](../../../system.xml.xpath/) 表达式的节点列表。

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | [XPath](../../../system.xml.xpath/) 表达式。 |

### 返回值

一个包含匹配 [XPath](../../../system.xml.xpath/) 查询的节点集合的 [XmlNodeList](../../xmlnodelist/)。

## XmlNode::SelectNodes(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) 方法

选择匹配 [XPath](../../../system.xml.xpath/) 表达式的节点列表。[XPath](../../../system.xml.xpath/) 表达式中找到的任何前缀均使用提供的 [XmlNamespaceManager](../../xmlnamespacemanager/) 进行解析。

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | [XPath](../../../system.xml.xpath/) 表达式。 |
| nsmgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | 用于解析 [XPath](../../../system.xml.xpath/) 表达式中前缀的命名空间的 [XmlNamespaceManager](../../xmlnamespacemanager/)。 |

### 返回值

一个包含匹配 [XPath](../../../system.xml.xpath/) 查询的节点集合的 [XmlNodeList](../../xmlnodelist/)。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlNodeList](../../xmlnodelist/)
* 类 [String](../../../system/string/)
* 类 [XmlNode](../)
* 类 [XmlNamespaceManager](../../xmlnamespacemanager/)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)