---
title: IsStartElement()
second_title: Aspose.Slides for C++ API リファレンス
description: "XmlReader::MoveToContent を呼び出し、現在のコンテンツノードが開始タグまたは空要素タグかどうかをテストします."
type: docs
weight: 885
url: /ja/system.xml/xmlreader/isstartelement/
---
## XmlReader::IsStartElement() メソッド

[XmlReader::MoveToContent](../movetocontent/) を呼び出し、現在のコンテンツノードが開始タグまたは空要素タグかどうかをテストします。

```cpp
virtual bool System::Xml::XmlReader::IsStartElement()
```

### 戻り値

**true** if [XmlReader::MoveToContent](../movetocontent/) finds a start tag or empty element tag; **false** if a node type other than [XmlNodeType::Element](../../xmlnodetype/) was found.

## XmlReader::IsStartElement(String) メソッド

[XmlReader::MoveToContent](../movetocontent/) を呼び出し、現在のコンテンツノードが開始タグまたは空要素タグかどうか、そして見つかった要素の [XmlReader::get_Name](../get_name/) 値が指定された引数と一致するかどうかをテストします。

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String name)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 要素の **Name** 値と照合される文字列。 |

### 戻り値

**true** if the resulting node is an element and the **Name** value matches the specified string. **false** if a node type other than [XmlNodeType::Element](../../xmlnodetype/) was found or if the element **Name** value does not match the specified string.

## XmlReader::IsStartElement(String, String) メソッド

[XmlReader::MoveToContent](../movetocontent/) を呼び出し、現在のコンテンツノードが開始タグまたは空要素タグかどうか、そして見つかった要素の [XmlReader::get_LocalName](../get_localname/) と [XmlReader::get_NamespaceURI](../get_namespaceuri/) の値がそれぞれ指定された文字列と一致するかどうかをテストします。

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String localname, String ns)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| localname | [String](../../../system/string/) | 要素の **LocalName** 値と照合される文字列。 |
| ns | [String](../../../system/string/) | 要素の **NamespaceURI** 値と照合される文字列。 |

### 戻り値

**true** if the resulting node is an element. **false** if a node type other than [XmlNodeType::Element](../../xmlnodetype/) was found or if the **LocalName** and **NamespaceURI** values of the element do not match the specified strings.

## 参考

* クラス [XmlReader](../)
* クラス [String](../../../system/string/)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)