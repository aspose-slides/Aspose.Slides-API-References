---
title: Create()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたファイル名を使用して新しい XmlWriter インスタンスを作成します。
type: docs
weight: 469
url: /ja/system.xml/xmlwriter/create/
---
## XmlWriter::Create(const String\&) メソッド

指定されたファイル名を使用して新しい[XmlWriter](../)インスタンスを作成します。

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputFileName | const [String](../../../system/string/)\& | 書き込み先のファイルです。[XmlWriter](../) は指定されたパスにファイルを作成し、XML 1.0 テキスト構文で書き込みます。**outputFileName** はファイルシステムのパスでなければなりません。 |

### 戻り値

[XmlWriter](../) オブジェクト。

## XmlWriter::Create(const String\&, SharedPtr\<XmlWriterSettings\>) メソッド

ファイル名と[XmlWriterSettings](../../xmlwritersettings/)オブジェクトを使用して新しい[XmlWriter](../)インスタンスを作成します。

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName, SharedPtr<XmlWriterSettings> settings)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputFileName | const [String](../../../system/string/)\& | 書き込み先のファイルです。[XmlWriter](../) は指定されたパスにファイルを作成し、XML 1.0 テキスト構文で書き込みます。**outputFileName** はファイルシステムのパスでなければなりません。 |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | 新しい[XmlWriter](../)インスタンスを構成するために使用する[XmlWriterSettings](../../xmlwritersettings/)オブジェクトです。**nullptr** の場合、デフォルト設定の[XmlWriterSettings](../../xmlwritersettings/)が使用されます。[XmlWriter](../) が XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) メソッドと併用される場合は、XslCompiledTransform::get_OutputSettings の値を使用して正しい設定を持つ[XmlWriterSettings](../../xmlwritersettings/)オブジェクトを取得すべきです。これにより、作成された[XmlWriter](../)オブジェクトが正しい出力設定を持つことが保証されます。 |

### 戻り値

[XmlWriter](../) オブジェクト。

## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&) メソッド

指定されたストリームを使用して新しい[XmlWriter](../)インスタンスを作成します。

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 書き込み先のストリームです。[XmlWriter](../) は XML 1.0 テキスト構文で書き込み、指定されたストリームに追記します。 |

### 戻り値

[XmlWriter](../) オブジェクト。

## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlWriterSettings\>) メソッド

ストリームと[XmlWriterSettings](../../xmlwritersettings/)オブジェクトを使用して新しい[XmlWriter](../)インスタンスを作成します。

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output, SharedPtr<XmlWriterSettings> settings)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 書き込み先のストリームです。[XmlWriter](../) は XML 1.0 テキスト構文で書き込み、指定されたストリームに追記します。 |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | 新しい[XmlWriter](../)インスタンスを構成する[XmlWriterSettings](../../xmlwritersettings/)オブジェクトです。**nullptr** の場合、デフォルト設定の[XmlWriterSettings](../../xmlwritersettings/)が使用されます。[XmlWriter](../) が XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) メソッドと併用される場合は、XslCompiledTransform::get_OutputSettings の値を使用して正しい設定を持つ[XmlWriterSettings](../../xmlwritersettings/)オブジェクトを取得すべきです。これにより、作成された[XmlWriter](../)オブジェクトが正しい出力設定を持つことが保証されます。 |

### 戻り値

[XmlWriter](../) オブジェクト。

## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&) メソッド

指定された TextWriter を使用して新しい[XmlWriter](../)インスタンスを作成します。

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | 書き込み先の TextWriter です。[XmlWriter](../) は XML 1.0 テキスト構文で書き込み、指定された TextWriter に追記します。 |

### 戻り値

[XmlWriter](../) オブジェクト。

## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&, SharedPtr\<XmlWriterSettings\>) メソッド

TextWriter と[XmlWriterSettings](../../xmlwritersettings/)オブジェクトを使用して新しい[XmlWriter](../)インスタンスを作成します。

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output, SharedPtr<XmlWriterSettings> settings)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | 書き込み先の TextWriter です。[XmlWriter](../) は XML 1.0 テキスト構文で書き込み、指定された TextWriter に追記します。 |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | 新しい[XmlWriter](../)インスタンスを構成する[XmlWriterSettings](../../xmlwritersettings/)オブジェクトです。**nullptr** の場合、デフォルト設定の[XmlWriterSettings](../../xmlwritersettings/)が使用されます。[XmlWriter](../) が XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) メソッドと併用される場合は、XslCompiledTransform::get_OutputSettings の値を使用して正しい設定を持つ[XmlWriterSettings](../../xmlwritersettings/)オブジェクトを取得すべきです。これにより、作成された[XmlWriter](../)オブジェクトが正しい出力設定を持つことが保証されます。 |

### 戻り値

[XmlWriter](../) オブジェクト。

## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&) メソッド

指定された[Text::StringBuilder](../../../system.text/stringbuilder/)を使用して新しい[XmlWriter](../)インスタンスを作成します。

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | 書き込み先の[Text::StringBuilder](../../../system.text/stringbuilder/)です。[XmlWriter](../) によって書き込まれたコンテンツは[Text::StringBuilder](../../../system.text/stringbuilder/)に追記されます。 |

### 戻り値

[XmlWriter](../) オブジェクト。

## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&, SharedPtr\<XmlWriterSettings\>) メソッド

[Text::StringBuilder](../../../system.text/stringbuilder/) と[XmlWriterSettings](../../xmlwritersettings/) オブジェクトを使用して新しい[XmlWriter](../)インスタンスを作成します。

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output, SharedPtr<XmlWriterSettings> settings)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | 書き込み先の[Text::StringBuilder](../../../system.text/stringbuilder/)です。[XmlWriter](../) によって書き込まれたコンテンツは[Text::StringBuilder](../../../system.text/stringbuilder/)に追記されます。 |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | 新しい[XmlWriter](../)インスタンスを構成する[XmlWriterSettings](../../xmlwritersettings/)オブジェクトです。**nullptr** の場合、デフォルト設定の[XmlWriterSettings](../../xmlwritersettings/)が使用されます。[XmlWriter](../) が XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) メソッドと併用される場合は、XslCompiledTransform::get_OutputSettings の値を使用して正しい設定を持つ[XmlWriterSettings](../../xmlwritersettings/)オブジェクトを取得すべきです。これにより、作成された[XmlWriter](../)オブジェクトが正しい出力設定を持つことが保証されます。 |

### 戻り値

[XmlWriter](../) オブジェクト。

## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&) メソッド

指定された[XmlWriter](../)オブジェクトを使用して新しい[XmlWriter](../)インスタンスを作成します。

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\& | 基礎となるライターとして使用したい[XmlWriter](../)オブジェクトです。 |

### 戻り値

指定された[XmlWriter](../)オブジェクトをラップした[XmlWriter](../)オブジェクト。

## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&, SharedPtr\<XmlWriterSettings\>) メソッド

指定された[XmlWriter](../) と[XmlWriterSettings](../../xmlwritersettings/) オブジェクトを使用して新しい[XmlWriter](../)インスタンスを作成します。

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output, SharedPtr<XmlWriterSettings> settings)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\& | 基礎となるライターとして使用したい[XmlWriter](../)オブジェクトです。 |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | 新しい[XmlWriter](../)インスタンスを構成する[XmlWriterSettings](../../xmlwritersettings/)オブジェクトです。**nullptr** の場合、デフォルト設定の[XmlWriterSettings](../../xmlwritersettings/)が使用されます。[XmlWriter](../) が XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) メソッドと併用される場合は、XslCompiledTransform::get_OutputSettings の値を使用して正しい設定を持つ[XmlWriterSettings](../../xmlwritersettings/)オブジェクトを取得すべきです。これにより、作成された[XmlWriter](../)オブジェクトが正しい出力設定を持つことが保証されます。 |

### 戻り値

指定された[XmlWriter](../)オブジェクトをラップした[XmlWriter](../)オブジェクト。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [String](../../../system/string/)
* Class [XmlWriterSettings](../../xmlwritersettings/)
* Class [Stream](../../../system.io/stream/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [StringBuilder](../../../system.text/stringbuilder/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)