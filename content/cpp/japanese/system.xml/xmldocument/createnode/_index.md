---
title: CreateNode()
second_title: Aspose.Slides for C++ API リファレンス
description: "指定された XmlNodeType、XmlNode::get_Prefix、XmlDocument::get_Name、XmlNode::get_NamespaceURI を使用して XmlNode を作成します。"
type: docs
weight: 482
url: /ja/system.xml/xmldocument/createnode/
---
## XmlDocument::CreateNode(XmlNodeType, const String\&, const String\&, const String\&) method

[XmlNode](../../xmlnode/) を作成します。指定された XmlNodeType、[XmlNode::get_Prefix](../../xmlnode/get_prefix/)、[XmlDocument::get_Name](../get_name/)、[XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) を使用します。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &prefix, const String &name, const String &namespaceURI)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | [XmlNodeType](../../xmlnodetype/) | 新しいノードの XmlNodeType。 |
| prefix | const [String](../../../system/string/)\& | 新しいノードのプレフィックス。 |
| name | const [String](../../../system/string/)\& | 新しいノードのローカル名。 |
| namespaceURI | const [String](../../../system/string/)\& | 新しいノードの名前空間 URI。 |

### 戻り値

新しい [XmlNode](../../xmlnode/)。

## XmlDocument::CreateNode(const String\&, const String\&, const String&) method

[XmlNode](../../xmlnode/) を作成します。指定されたノードタイプ、[XmlDocument::get_Name](../get_name/)、[XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) を使用します。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(const String &nodeTypeString, const String &name, const String &namespaceURI)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| nodeTypeString | const [String](../../../system/string/)\& | [String](../../../system/string/) バージョンの新しいノードの XmlNodeType。このパラメータは以下の表に示す値のいずれかでなければなりません。 |
| name | const [String](../../../system/string/)\& | 新しいノードの修飾名。名前にコロンが含まれる場合、[XmlNode::get_Prefix](../../xmlnode/get_prefix/) と [XmlDocument::get_LocalName](../get_localname/) コンポーネントに分割されます。 |
| namespaceURI | const [String](../../../system/string/)\& | 新しいノードの名前空間 URI。 |

### 戻り値

新しい [XmlNode](../../xmlnode/)。

## 備考

**nodeTypeString** パラメータは大文字小文字を区別し、以下の表のいずれかの値でなければなりません: 

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

## XmlDocument::CreateNode(XmlNodeType, const String\&, const String\&) method

[XmlNode](../../xmlnode/) を作成します。指定された XmlNodeType、[XmlDocument::get_Name](../get_name/)、[XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) を使用します。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &name, const String &namespaceURI)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | [XmlNodeType](../../xmlnodetype/) | 新しいノードの XmlNodeType。 |
| name | const [String](../../../system/string/)\& | 新しいノードの修飾名。名前にコロンが含まれる場合、[XmlNode::get_Prefix](../../xmlnode/get_prefix/) と [XmlDocument::get_LocalName](../get_localname/) コンポーネントに分割されます。 |
| namespaceURI | const [String](../../../system/string/)\& | 新しいノードの名前空間 URI。 |

### 戻り値

新しい [XmlNode](../../xmlnode/)。

## 参照

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)