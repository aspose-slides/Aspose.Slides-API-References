---
title: CreateNode()
second_title: Aspose.Slides C++ API 参考
description: "使用指定的 XmlNodeType、XmlNode::get_Prefix、XmlDocument::get_Name 和 XmlNode::get_NamespaceURI 创建一个 XmlNode。"
type: docs
weight: 482
url: /zh/system.xml/xmldocument/createnode/
---
## XmlDocument::CreateNode(XmlNodeType, const String\&, const String\&, const String\&) 方法

使用指定的 XmlNodeType、[XmlNode::get_Prefix](../../xmlnode/get_prefix/)、[XmlDocument::get_Name](../get_name/)和[XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/)创建一个 [XmlNode](../../xmlnode/)。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &prefix, const String &name, const String &namespaceURI)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| type | [XmlNodeType](../../xmlnodetype/) | 新节点的 XmlNodeType。 |
| prefix | const [String](../../../system/string/)\& | 新节点的前缀。 |
| name | const [String](../../../system/string/)\& | 新节点的本地名称。 |
| namespaceURI | const [String](../../../system/string/)\& | 新节点的命名空间 URI。 |

### 返回值

新 [XmlNode](../../xmlnode/)。

## XmlDocument::CreateNode(const String\&, const String\&, const String\&) 方法

使用指定的节点类型、[XmlDocument::get_Name](../get_name/)和[XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/)创建一个 [XmlNode](../../xmlnode/)。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(const String &nodeTypeString, const String &name, const String &namespaceURI)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| nodeTypeString | const [String](../../../system/string/)\& | [String](../../../system/string/) 版本的 XmlNodeType（新节点）。此参数必须是下表中列出的值之一。 |
| name | const [String](../../../system/string/)\& | 新节点的限定名称。如果名称包含冒号，则会被解析为 [XmlNode::get_Prefix](../../xmlnode/get_prefix/) 和 [XmlDocument::get_LocalName](../get_localname/) 组件。 |
| namespaceURI | const [String](../../../system/string/)\& | 新节点的命名空间 URI。 |

### 返回值

新 [XmlNode](../../xmlnode/)。

## 备注

**nodeTypeString** 参数区分大小写，且必须是下表中的其中一个值：

| nodeTypeString| XmlNodeType |
| --- | --- |
| attribute| [Attribute](../../../system/attribute/)|
| cdatasection| CDATA |
| comment| Comment |
| document| Document |
| documentfragment| DocumentFragment |
| documenttype| DocumentType |
| element| Element |
| entityreference| EntityReference |
| processinginstruction| ProcessingInstruction |
| significantwhitespace| SignificantWhitespace |
| text| [Text](../../../system.text/)|
| whitespace| Whitespace |

## XmlDocument::CreateNode(XmlNodeType, const String\&, const String\&) 方法

使用指定的 XmlNodeType、[XmlDocument::get_Name](../get_name/)和[XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/)创建一个 [XmlNode](../../xmlnode/)。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &name, const String &namespaceURI)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| type | [XmlNodeType](../../xmlnodetype/) | 新节点的 XmlNodeType。 |
| name | const [String](../../../system/string/)\& | 新节点的限定名称。如果名称包含冒号，则会被解析为 [XmlNode::get_Prefix](../../xmlnode/get_prefix/) 和 [XmlDocument::get_LocalName](../get_localname/) 组件。 |
| namespaceURI | const [String](../../../system/string/)\& | 新节点的命名空间 URI。 |

### 返回值

新 [XmlNode](../../xmlnode/)。

## 另见

* 枚举 [XmlNodeType](../../xmlnodetype/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlNode](../../xmlnode/)
* 类 [String](../../../system/string/)
* 类 [XmlDocument](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)