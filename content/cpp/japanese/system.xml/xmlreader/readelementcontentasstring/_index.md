---
title: ReadElementContentAsString()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在の要素を読み取り、その内容を String オブジェクトとして返します。
type: docs
weight: 573
url: /ja/system.xml/xmlreader/readelementcontentasstring/
---
## XmlReader::ReadElementContentAsString() メソッド

現在の要素を読み取り、その内容を [String](../../../system/string/) オブジェクトとして返します。

```cpp
virtual String System::Xml::XmlReader::ReadElementContentAsString()
```

### 戻り値

要素の内容を [String](../../../system/string/) オブジェクトとして返します。

## XmlReader::ReadElementContentAsString(String, String) メソッド

指定されたローカル名と名前空間 URI が現在の要素と一致することを確認し、現在の要素を読み取って、その内容を [String](../../../system/string/) オブジェクトとして返します。

```cpp
virtual String System::Xml::XmlReader::ReadElementContentAsString(String localName, String namespaceURI)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 要素のローカル名です。 |
| namespaceURI | [String](../../../system/string/) | 要素の名前空間 URI です。 |

### 戻り値

要素の内容を [String](../../../system/string/) オブジェクトとして返します。

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)