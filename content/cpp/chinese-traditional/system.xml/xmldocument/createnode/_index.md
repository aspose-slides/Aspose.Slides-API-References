---
title: CreateNode()
second_title: Aspose.Slides for C++ API 參考
description: "建立具有指定 XmlNodeType、XmlNode::get_Prefix、XmlDocument::get_Name 和 XmlNode::get_NamespaceURI 的 XmlNode。"
type: docs
weight: 482
url: /zh-hant/system.xml/xmldocument/createnode/
---
## XmlDocument::CreateNode(XmlNodeType, const String&, const String&, const String&) 方法

建立一個 [XmlNode](../../xmlnode/)，其指定的 XmlNodeType、[XmlNode::get_Prefix](../../xmlnode/get_prefix/)、[XmlDocument::get_Name](../get_name/) 和 [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/)。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &prefix, const String &name, const String &namespaceURI)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| type | [XmlNodeType](../../xmlnodetype/) | 新節點的 XmlNodeType。 |
| prefix | const [String](../../../system/string/)\& | 新節點的前綴。 |
| name | const [String](../../../system/string/)\& | 新節點的本地名稱。 |
| namespaceURI | const [String](../../../system/string/)\& | 新節點的命名空間 URI。 |

### 回傳值

新的[XmlNode](../../xmlnode/)。

## XmlDocument::CreateNode(const String&, const String&, const String&) 方法

建立一個 [XmlNode](../../xmlnode/)，其指定的節點類型、[XmlDocument::get_Name](../get_name/) 和 [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/)。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(const String &nodeTypeString, const String &name, const String &namespaceURI)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| nodeTypeString | const [String](../../../system/string/)\& | [String](../../../system/string/) 版的 XmlNodeType。此參數必須是下表中列出的值之一。 |
| name | const [String](../../../system/string/)\& | 新節點的限定名稱。若名稱包含冒號，則會被解析為 [XmlNode::get_Prefix](../../xmlnode/get_prefix/) 和 [XmlDocument::get_LocalName](../get_localname/) 組件。 |
| namespaceURI | const [String](../../../system/string/)\& | 新節點的命名空間 URI。 |

### 回傳值

新的[XmlNode](../../xmlnode/)。

## 備註

**nodeTypeString** 參數區分大小寫，且必須是以下表格中的其中一個值：

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

## XmlDocument::CreateNode(XmlNodeType, const String&, const String&) 方法

建立一個 [XmlNode](../../xmlnode/)，其指定的 XmlNodeType、[XmlDocument::get_Name](../get_name/) 和 [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/)。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &name, const String &namespaceURI)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| type | [XmlNodeType](../../xmlnodetype/) | 新節點的 XmlNodeType。 |
| name | const [String](../../../system/string/)\& | 新節點的限定名稱。若名稱包含冒號則會被解析為 [XmlNode::get_Prefix](../../xmlnode/get_prefix/) 和 [XmlDocument::get_LocalName](../get_localname/) 組件。 |
| namespaceURI | const [String](../../../system/string/)\& | 新節點的命名空間 URI。 |

### 回傳值

新的[XmlNode](../../xmlnode/)。

## 參見

* 列舉 [XmlNodeType](../../xmlnodetype/)
* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlNode](../../xmlnode/)
* 類別 [String](../../../system/string/)
* 類別 [XmlDocument](../)
* 命名空間 [System::Xml](../../)
* 程式庫 [Aspose.Slides](../../../)