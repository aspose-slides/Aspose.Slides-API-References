---
title: ReadElementString()
second_title: Aspose.Slides for C++ API リファレンス
description: "テキストのみの要素を読み取ります。ただし、この操作をよりシンプルに処理できるため、代わりに XmlReader::ReadElementContentAsString メソッドを使用することが推奨されます。"
type: docs
weight: 859
url: /ja/system.xml/xmlreader/readelementstring/
---
## XmlReader::ReadElementString() メソッド

テキストのみの要素を読み取ります。ただし、この操作をよりシンプルに処理できるため、代わりに [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) メソッドを使用することが推奨されます。

```cpp
virtual String System::Xml::XmlReader::ReadElementString()
```

### 戻り値

読み取られた要素に含まれるテキスト。要素が空の場合は空文字列。

## XmlReader::ReadElementString(String) メソッド

テキストのみの要素を読み取る前に、見つかった要素の [XmlReader::get_Name](../get_name/) 値が指定された文字列と一致するか確認します。ただし、この操作をよりシンプルに処理できるため、代わりに [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) メソッドを使用することが推奨されます。

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String name)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 確認する名前。 |

### 戻り値

読み取られた要素に含まれるテキスト。要素が空の場合は空文字列。

## XmlReader::ReadElementString(String, String) メソッド

テキストのみの要素を読み取る前に、見つかった要素の [XmlReader::get_LocalName](../get_localname/) と [XmlReader::get_NamespaceURI](../get_namespaceuri/) の値がそれぞれ指定された文字列と一致するか確認します。ただし、この操作をよりシンプルに処理できるため、代わりに [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) メソッドを使用することが推奨されます。

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String localname, String ns)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| localname | [String](../../../system/string/) | 確認するローカル名。 |
| ns | [String](../../../system/string/) | 確認する名前空間 URI。 |

### 戻り値

読み取られた要素に含まれるテキスト。要素が空の場合は空文字列。

## 関連項目

* クラス [String](../../../system/string/)
* クラス [XmlReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)