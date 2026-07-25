---
title: ReadToNextSibling()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された完全修飾名を持つ次の兄弟要素へ XmlReader を進めます。
type: docs
weight: 924
url: /ja/system.xml/xmlreader/readtonextsibling/
---
## XmlReader::ReadToNextSibling(String) メソッド

指定された完全修飾名を持つ次の兄弟要素へ [XmlReader](../) を進めます。

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String name)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 移動したい兄弟要素の完全修飾名。 |

### 戻り値

**true** if a matching sibling element is found; otherwise **false**. 一致する兄弟要素が見つからない場合、[XmlReader](../) は親要素の終了タグ（[XmlReader::get_NodeType](../get_nodetype/) の値は [XmlNodeType::EndElement](../../xmlnodetype/)）に位置します。

## XmlReader::ReadToNextSibling(String, String) メソッド

指定されたローカル名と名前空間 URI を持つ次の兄弟要素へ [XmlReader](../) を進めます。

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String localName, String namespaceURI)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 移動したい兄弟要素のローカル名。 |
| namespaceURI | [String](../../../system/string/) | 移動したい兄弟要素の名前空間 URI。 |

### 戻り値

**true** if a matching sibling element is found; otherwise **false**. 一致する兄弟要素が見つからない場合、[XmlReader](../) は親要素の終了タグ（[XmlReader::get_NodeType](../get_nodetype/) の値は [XmlNodeType::EndElement](../../xmlnodetype/)）に位置します。

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)