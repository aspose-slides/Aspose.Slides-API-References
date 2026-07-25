---
title: CreateElement()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された名前で要素を作成します。
type: docs
weight: 339
url: /ja/system.xml/xmldocument/createelement/
---
## XmlDocument::CreateElement(const String\&) method

指定された名前で要素を作成します。

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &name)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | 要素の修飾名です。名前にコロンが含まれる場合、[XmlNode::get_Prefix](../../xmlnode/get_prefix/) の値はコロンの前の部分を、[XmlDocument::get_LocalName](../get_localname/) の値はコロンの後の部分を表します。修飾名には **xmlns** プレフィックスを含めることはできません。 |

### 戻り値

新しい[XmlElement](../../xmlelement/)です。

## XmlDocument::CreateElement(const String\&, const String\&) method

修飾名と[XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) を使用して[XmlElement](../../xmlelement/)を作成します。

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &qualifiedName, const String &namespaceURI)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| qualifiedName | const [String](../../../system/string/)\& | 要素の修飾名です。名前にコロンが含まれる場合、[XmlNode::get_Prefix](../../xmlnode/get_prefix/) の値はコロンの前の部分を、[XmlDocument::get_LocalName](../get_localname/) の値はコロンの後の部分を表します。修飾名には **xmlns** プレフィックスを含めることはできません。 |
| namespaceURI | const [String](../../../system/string/)\& | 要素の名前空間 URIです。 |

### 戻り値

新しい[XmlElement](../../xmlelement/)です。

## XmlDocument::CreateElement(const String\&, const String\&, const String\&) method

指定された[XmlNode::get_Prefix](../../xmlnode/get_prefix/)、[XmlDocument::get_LocalName](../get_localname/)、[XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/)を使用して要素を作成します。

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &prefix, const String &localName, const String &namespaceURI)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 新しい要素のプレフィックスです（存在する場合）。[String::Empty](../../../system/string/empty/) と **nullptr** は同等です。 |
| localName | const [String](../../../system/string/)\& | 新しい要素のローカル名です。 |
| namespaceURI | const [String](../../../system/string/)\& | 新しい要素の名前空間 URIです（存在する場合）。[String::Empty](../../../system/string/empty/) と **nullptr** は同等です。 |

### 戻り値

新しい[XmlElement](../../xmlelement/)です。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [XmlElement](../../xmlelement/)
* クラス [String](../../../system/string/)
* クラス [XmlDocument](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)