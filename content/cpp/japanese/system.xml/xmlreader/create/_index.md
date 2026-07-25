---
title: Create()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された URI で新しい XmlReader インスタンスを作成します。
type: docs
weight: 1015
url: /ja/system.xml/xmlreader/create/
---
## XmlReader::Create(const String\&) メソッド

指定された URI を使用して新しい [XmlReader](../) インスタンスを作成します。

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | XML データを含むファイルの URI です。[XmlUrlResolver](../../xmlurlresolver/) クラスはパスを標準データ表現に変換するために使用されます。 |

### 戻り値

ストリーム内の XML データを読み取るために使用されるオブジェクト。

## XmlReader::Create(const String\&, const SharedPtr\<XmlReaderSettings\>\&) メソッド

指定された URI と設定を使用して新しい [XmlReader](../) インスタンスを作成します。

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, const SharedPtr<XmlReaderSettings> &settings)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | XML データを含むファイルの URI です。[XmlReaderSettings](../../xmlreadersettings/) オブジェクト上の [XmlResolver](../../xmlresolver/) オブジェクトはパスを標準データ表現に変換するために使用されます。XmlReaderSettings::get_XmlResolver の値が **nullptr** の場合、新しい [XmlUrlResolver](../../xmlurlresolver/) オブジェクトが使用されます。 |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | 新しい [XmlReader](../) インスタンスの設定です。この値は **nullptr** でも構いません。 |

### 戻り値

ストリーム内の XML データを読み取るために使用されるオブジェクト。

## XmlReader::Create(const String\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) メソッド

指定された URI、設定、および解析用コンテキスト情報を使用して新しい [XmlReader](../) インスタンスを作成します。

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | XML データを含むファイルの URI です。[XmlReaderSettings](../../xmlreadersettings/) オブジェクト上の [XmlResolver](../../xmlresolver/) オブジェクトはパスを標準データ表現に変換するために使用されます。XmlReaderSettings::get_XmlResolver の値が **nullptr** の場合、新しい [XmlUrlResolver](../../xmlurlresolver/) オブジェクトが使用されます。 |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | 新しい [XmlReader](../) インスタンスの設定です。この値は **nullptr** でも構いません。 |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | XML フラグメントを解析するために必要なコンテキスト情報です。コンテキスト情報には使用する [XmlNameTable](../../xmlnametable/)、エンコーディング、名前空間スコープ、現在の **xml:lang** と **xml:space** のスコープ、ベース URI、および文書型定義が含まれる場合があります。この値は **nullptr** でも構いません。 |

### 戻り値

ストリーム内の XML データを読み取るために使用されるオブジェクト。

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&) メソッド

デフォルト設定で指定されたストリームを使用して新しい [XmlReader](../) インスタンスを作成します。

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | XML データを含むストリームです。[XmlReader](../) はストリームの最初のバイトをスキャンし、バイトオーダーマークやエンコーディングの手掛かりを探します。エンコーディングが判明すると、そのエンコーディングを使用してストリームの読み取りを続行し、（Unicode）文字のストリームとして入力の解析が続行されます。 |

### 戻り値

ストリーム内の XML データを読み取るために使用されるオブジェクト。

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlReaderSettings\>\&) メソッド

指定されたストリームと設定で新しい [XmlReader](../) インスタンスを作成します。

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlReaderSettings> &settings)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | XML データを含むストリームです。[XmlReader](../) はストリームの最初のバイトをスキャンし、バイトオーダーマークやエンコーディングの手掛かりを探します。エンコーディングが判明すると、そのエンコーディングを使用してストリームの読み取りを続行し、（Unicode）文字のストリームとして入力の解析が続行されます。 |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | 新しい [XmlReader](../) インスタンスの設定です。この値は **nullptr** でも構いません。 |

### 戻り値

ストリーム内の XML データを読み取るために使用されるオブジェクト。

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) メソッド

指定されたストリーム、ベース URI、設定で新しい [XmlReader](../) インスタンスを作成します。

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | XML データを含むストリームです。[XmlReader](../) はストリームの最初のバイトをスキャンし、バイトオーダーマークやエンコーディングの手掛かりを探します。エンコーディングが判明すると、そのエンコーディングを使用してストリームの読み取りを続行し、（Unicode）文字のストリームとして入力の解析が続行されます。 |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | 新しい [XmlReader](../) インスタンスの設定です。この値は **nullptr** でも構いません。 |
| baseUri | const [String](../../../system/string/)\& | 読み取るエンティティまたはドキュメントのベース URI です。この値は **nullptr** でも構いません。 **[Security](../../../system.security/) Note** ベース URI は XML ドキュメントの相対 URI を解決するために使用されます。信頼できないソースからのベース URI は使用しないでください。 |

### 戻り値

ストリーム内の XML データを読み取るために使用されるオブジェクト。

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) メソッド

指定されたストリーム、設定、および解析用コンテキスト情報で新しい [XmlReader](../) インスタンスを作成します。

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | XML データを含むストリームです。[XmlReader](../) はストリームの最初のバイトをスキャンし、バイトオーダーマークやエンコーディングの手掛かりを探します。エンコーディングが判明すると、そのエンコーディングを使用してストリームの読み取りを続行し、（Unicode）文字のストリームとして入力の解析が続行されます。 |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | 新しい [XmlReader](../) インスタンスの設定です。この値は **nullptr** でも構いません。 |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | XML フラグメントを解析するために必要なコンテキスト情報です。コンテキスト情報には使用する [XmlNameTable](../../xmlnametable/)、エンコーディング、名前空間スコープ、現在の **xml:lang** と **xml:space** のスコープ、ベース URI、および文書型定義が含まれる場合があります。この値は **nullptr** でも構いません。 |

### 戻り値

ストリーム内の XML データを読み取るために使用されるオブジェクト。

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&) メソッド

指定されたテキストリーダーを使用して新しい [XmlReader](../) インスタンスを作成します。

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | XML データを読み取るテキストリーダーです。テキストリーダーは Unicode 文字のストリームを返すため、XML 宣言で指定されたエンコーディングは XML リーダーによってデータストリームのデコードに使用されません。 |

### 戻り値

ストリーム内の XML データを読み取るために使用されるオブジェクト。

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlReaderSettings\>\&) メソッド

指定されたテキストリーダーと設定で新しい [XmlReader](../) インスタンスを作成します。

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlReaderSettings> &settings)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | XML データを読み取るテキストリーダーです。テキストリーダーは Unicode 文字のストリームを返すため、XML 宣言で指定されたエンコーディングは XML リーダーによってデータストリームのデコードに使用されません。 |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | 新しい [XmlReader](../) の設定です。この値は **nullptr** でも構いません。 |

### 戻り値

ストリーム内の XML データを読み取るために使用されるオブジェクト。

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) メソッド

指定されたテキストリーダー、設定、およびベース URI を使用して新しい [XmlReader](../) インスタンスを作成します。

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | XML データを読み取るテキストリーダーです。テキストリーダーは Unicode 文字のストリームを返すため、XML 宣言で指定されたエンコーディングは [XmlReader](../) によってデータストリームのデコードに使用されません。 |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | 新しい [XmlReader](../) インスタンスの設定です。この値は **nullptr** でも構いません。 |
| baseUri | const [String](../../../system/string/)\& | 読み取るエンティティまたはドキュメントのベース URI です。この値は **nullptr** でも構いません。 **[Security](../../../system.security/) Note** ベース URI は XML ドキュメントの相対 URI を解決するために使用されます。信頼できないソースからのベース URI は使用しないでください。 |

### 戻り値

ストリーム内の XML データを読み取るために使用されるオブジェクト。

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) メソッド

指定されたテキストリーダー、設定、および解析用コンテキスト情報で新しい [XmlReader](../) インスタンスを作成します。

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | XML データを読み取るテキストリーダーです。テキストリーダーは Unicode 文字のストリームを返すため、XML 宣言で指定されたエンコーディングは XML リーダーによってデータストリームのデコードに使用されません。 |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | 新しい [XmlReader](../) インスタンスの設定です。この値は **nullptr** でも構いません。 |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | XML フラグメントを解析するために必要なコンテキスト情報です。コンテキスト情報には使用する [XmlNameTable](../../xmlnametable/)、エンコーディング、名前空間スコープ、現在の **xml:lang** と **xml:space** のスコープ、ベース URI、および文書型定義が含まれる場合があります。この値は **nullptr** でも構いません。 |

### 戻り値

ストリーム内の XML データを読み取るために使用されるオブジェクト。

## XmlReader::Create(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlReaderSettings\>) メソッド

指定された XML リーダーと設定で新しい [XmlReader](../) インスタンスを作成します。

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<XmlReader> &reader, SharedPtr<XmlReaderSettings> settings)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../)\>\& | 基礎となる XML リーダーとして使用したいオブジェクトです。 |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | 新しい [XmlReader](../) インスタンスの設定です。[XmlReaderSettings](../../xmlreadersettings/) オブジェクトの適合レベルは、基礎となるリーダーの適合レベルと一致するか、[ConformanceLevel::Auto](../../conformancelevel/) に設定する必要があります。 |

### 戻り値

指定された [XmlReader](../) オブジェクトをラップしたオブジェクトです。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [XmlReader](../)
* クラス [String](../../../system/string/)
* クラス [XmlReaderSettings](../../xmlreadersettings/)
* クラス [XmlParserContext](../../xmlparsercontext/)
* クラス [Stream](../../../system.io/stream/)
* クラス [TextReader](../../../system.io/textreader/)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)