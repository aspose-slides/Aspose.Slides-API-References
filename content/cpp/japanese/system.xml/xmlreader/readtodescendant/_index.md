---
title: ReadToDescendant()
second_title: Aspose.Slides for C++ APIリファレンス
description: 指定された修飾名を持つ次の子孫要素へ XmlReader を進めます。
type: docs
weight: 911
url: /ja/system.xml/xmlreader/readtodescendant/
---
## XmlReader::ReadToDescendant(String) メソッド

[XmlReader](../) を、指定された修飾名を持つ次の子孫要素へ進めます。

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String name)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 移動したい要素の修飾名です。 |

### 戻り値

**true** が返されるのは、一致する子孫要素が見つかった場合です。そうでない場合は **false** です。一致する子要素が見つからない場合、[XmlReader](../) は要素の終了タグ（[XmlReader::get_NodeType](../get_nodetype/) の値は [XmlNodeType::EndElement](../../xmlnodetype/)）に位置します。[XmlReader::ReadToDescendant(String)](./) が呼び出されたときに [XmlReader](../) が要素上に位置していない場合、このメソッドは **false** を返し、[XmlReader](../) の位置は変更されません。

## XmlReader::ReadToDescendant(String, String) メソッド

[XmlReader](../) を、指定されたローカル名と名前空間URIを持つ次の子孫要素へ進めます。

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String localName, String namespaceURI)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 移動したい要素のローカル名です。 |
| namespaceURI | [String](../../../system/string/) | 移動したい要素の名前空間URIです。 |

### 戻り値

**true** が返されるのは、一致する子孫要素が見つかった場合です。そうでない場合は **false** です。一致する子要素が見つからない場合、[XmlReader](../) は要素の終了タグ（[XmlReader::get_NodeType](../get_nodetype/) の値は [XmlNodeType::EndElement](../../xmlnodetype/)）に位置します。[XmlReader::ReadToDescendant(String,String)](./) が呼び出されたときに [XmlReader](../) が要素上に位置していない場合、このメソッドは **false** を返し、[XmlReader](../) の位置は変更されません。

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)