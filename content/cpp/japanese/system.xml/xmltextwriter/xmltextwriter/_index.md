---
title: XmlTextWriter()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたストリームとエンコーディングを使用して、XmlTextWriter クラスのインスタンスを作成します。
type: docs
weight: 183
url: /ja/system.xml/xmltextwriter/xmltextwriter/
---
## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Text::Encoding\>\&) コンストラクタ

指定されたストリームとエンコーディングを使用して、[XmlTextWriter](../) クラスのインスタンスを作成します。

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::Stream> &w, const SharedPtr<Text::Encoding> &encoding)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| w | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 書き込み先のストリーム。 |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | 生成するエンコーディング。encoding が **nullptr** の場合、ストリームを UTF-8 として書き出し、**ProcessingInstruction** からエンコーディング属性を省略します。 |

## XmlTextWriter::XmlTextWriter(const String\&, const SharedPtr\<Text::Encoding\>\&) コンストラクタ

指定されたファイルを使用して、[XmlTextWriter](../) クラスのインスタンスを作成します。

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const String &filename, const SharedPtr<Text::Encoding> &encoding)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 書き込み対象のファイル名。ファイルが存在する場合、内容を切り捨てて新しい内容で上書きします。 |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | 生成するエンコーディング。encoding が **nullptr** の場合、ファイルを UTF-8 として書き出し、**ProcessingInstruction** からエンコーディング属性を省略します。 |

## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::TextWriter\>\&) コンストラクタ

指定された TextWriter を使用して、[XmlTextWriter](../) クラスのインスタンスを作成します。

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::TextWriter> &w)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| w | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | 書き込み先の TextWriter。TextWriter が既に正しいエンコーディングに設定されていると想定します。 |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Stream](../../../system.io/stream/)
* クラス [Encoding](../../../system.text/encoding/)
* クラス [XmlTextWriter](../)
* クラス [String](../../../system/string/)
* クラス [TextWriter](../../../system.io/textwriter/)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)