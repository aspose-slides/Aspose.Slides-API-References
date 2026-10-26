---
title: SelectSingleNode()
second_title: Aspose.Slides for C++ API 参考
description: 选择匹配 XPath 表达式的第一个 XmlNode。
type: docs
weight: 352
url: /zh/system.xml/xmlnode/selectsinglenode/
---
## XmlNode::SelectSingleNode(const String\&) 方法

选择匹配 [XPath](../../../system.xml.xpath/) 表达式的第一个 [XmlNode](../)。

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | [XPath](../../../system.xml.xpath/) 表达式。 |

### 返回值

匹配 [XPath](../../../system.xml.xpath/) 查询的第一个 [XmlNode](../)，如果未找到匹配的节点，则返回 **nullptr**。

## XmlNode::SelectSingleNode(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) 方法

选择匹配 [XPath](../../../system.xml.xpath/) 表达式的第一个 [XmlNode](../)。在 [XPath](../../../system.xml.xpath/) 表达式中找到的任何前缀都使用提供的 [XmlNamespaceManager](../../xmlnamespacemanager/) 进行解析。

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | [XPath](../../../system.xml.xpath/) 表达式。 |
| nsmgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | 用于在 [XPath](../../../system.xml.xpath/) 表达式中解析前缀命名空间的 [XmlNamespaceManager](../../xmlnamespacemanager/)。 |

### 返回值

匹配 [XPath](../../../system.xml.xpath/) 查询的第一个 [XmlNode](../)，如果未找到匹配的节点，则返回 **nullptr**。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlNode](../)
* 类 [String](../../../system/string/)
* 类 [XmlNamespaceManager](../../xmlnamespacemanager/)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)