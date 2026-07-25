---
title: ReadToFollowing()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された修飾名を持つ要素が見つかるまで読み取ります。
type: docs
weight: 898
url: /ja/system.xml/xmlreader/readtofollowing/
---
## XmlReader::ReadToFollowing(String) メソッド

指定された修飾名を持つ要素が見つかるまで読み取ります。

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String name)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 要素の修飾名。 |

### 戻り値

**true** が返されます。一致する要素が見つかった場合は **true**、それ以外の場合は **false** が返され、 [XmlReader](../) はファイルの終端状態になります。

## XmlReader::ReadToFollowing(String, String) メソッド

指定されたローカル名と名前空間URIを持つ要素が見つかるまで読み取ります。

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String localName, String namespaceURI)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 要素のローカル名。 |
| namespaceURI | [String](../../../system/string/) | 要素の名前空間URI。 |

### 戻り値

**true** が返されます。一致する要素が見つかった場合は **true**、それ以外の場合は **false** が返され、 [XmlReader](../) はファイルの終端状態になります。

## 関連項目

* クラス [String](../../../system/string/)
* クラス [XmlReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)