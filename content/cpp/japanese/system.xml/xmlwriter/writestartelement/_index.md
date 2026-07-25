---
title: WriteStartElement()
second_title: Aspose.Slides for C++ API リファレンス
description: 派生クラスでオーバーライドされた場合、指定された開始タグを書き込み、指定された名前空間に関連付けます。
type: docs
weight: 92
url: /ja/system.xml/xmlwriter/writestartelement/
---
## XmlWriter::WriteStartElement(const String\&, const String\&) method

派生クラスでオーバーライドされた場合、指定された開始タグを書き込み、指定された名前空間に関連付けます。

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName, const String &ns)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | 要素のローカル名です。 |
| ns | const [String](../../../system/string/)\& | 要素に関連付ける名前空間 URI。この名前空間がすでにスコープ内にあり、関連付けられたプレフィックスがある場合、ライターは自動的にそのプレフィックスも書き込みます。 |

## XmlWriter::WriteStartElement(const String\&, const String\&, const String\&) method

派生クラスでオーバーライドされた場合、指定された開始タグを書き込み、指定された名前空間とプレフィックスに関連付けます。

```cpp
virtual void System::Xml::XmlWriter::WriteStartElement(const String &prefix, const String &localName, const String &ns)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 要素の名前空間プレフィックスです。 |
| localName | const [String](../../../system/string/)\& | 要素のローカル名です。 |
| ns | const [String](../../../system/string/)\& | 要素に関連付ける名前空間 URIです。 |

## XmlWriter::WriteStartElement(const String\&) method

派生クラスでオーバーライドされた場合、指定されたローカル名で開始タグを書き出します。

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | 要素のローカル名です。 |

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlWriter](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)