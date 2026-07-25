---
title: XmlTextReader()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたストリームで XmlTextReader クラスの新しいインスタンスを初期化します。
type: docs
weight: 482
url: /ja/system.xml/xmltextreader/xmltextreader/
---
## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&) コンストラクタ

指定されたストリームで、[XmlTextReader](../) クラスの新しいインスタンスを初期化します。

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | XML データを読み込むストリーム。 |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&) コンストラクタ

指定された URL とストリームで、[XmlTextReader](../) クラスの新しいインスタンスを初期化します。

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | 外部リソースの解決に使用する URL。[XmlTextReader::get_BaseURI](../get_baseuri/) はこの値に設定されます。 |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | XML データを読み込むストリーム。 |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) コンストラクタ

指定されたストリームと [XmlNameTable](../../xmlnametable/) で、[XmlTextReader](../) クラスの新しいインスタンスを初期化します。

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | XML データを読み込むストリーム。 |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | 使用する [XmlNameTable](../../xmlnametable/)。 |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) コンストラクタ

指定された URL、ストリーム、[XmlNameTable](../../xmlnametable/) で、[XmlTextReader](../) クラスの新しいインスタンスを初期化します。

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | 外部リソースの解決に使用する URL。[XmlTextReader::get_BaseURI](../get_baseuri/) はこの値に設定されます。**url** が **nullptr** の場合、**BaseURI** は [String::Empty](../../../system/string/empty/) に設定されます。 |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | XML データを読み込むストリーム。 |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | 使用する [XmlNameTable](../../xmlnametable/)。 |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&) コンストラクタ

指定された TextReader で、[XmlTextReader](../) クラスの新しいインスタンスを初期化します。

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | XML データを読み込む TextReader。 |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&) コンストラクタ

指定された URL と TextReader で、[XmlTextReader](../) クラスの新しいインスタンスを初期化します。

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | 外部リソースの解決に使用する URL。[XmlTextReader::get_BaseURI](../get_baseuri/) はこの値に設定されます。 |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | XML データを読み込む TextReader。 |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) コンストラクタ

指定された TextReader と [XmlNameTable](../../xmlnametable/) で、[XmlTextReader](../) クラスの新しいインスタンスを初期化します。

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | XML データを読み込む TextReader。 |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | 使用する [XmlNameTable](../../xmlnametable/)。 |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) コンストラクタ

指定された URL、TextReader、[XmlNameTable](../../xmlnametable/) で、[XmlTextReader](../) クラスの新しいインスタンスを初期化します。

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | 外部リソースの解決に使用する URL。[XmlTextReader::get_BaseURI](../get_baseuri/) はこの値に設定されます。**url** が **nullptr** の場合、**BaseURI** は [String::Empty](../../../system/string/empty/) に設定されます。 |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | XML データを読み込む TextReader。 |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | 使用する [XmlNameTable](../../xmlnametable/)。 |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) コンストラクタ

指定されたストリーム、XmlNodeType、[XmlParserContext](../../xmlparsercontext/) で、[XmlTextReader](../) クラスの新しいインスタンスを初期化します。

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| xmlFragment | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | XML フラグメントを含むストリーム。 |
| fragType | [XmlNodeType](../../xmlnodetype/) | XML フラグメントの XmlNodeType。フラグメントが含められる内容も決定します。 |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | **xmlFragment** を解析する [XmlParserContext](../../xmlparsercontext/)。使用する [XmlNameTable](../../xmlnametable/)、エンコーディング、名前空間スコープ、現在の **xml:lang**、および **xml:space** スコープを含みます。 |

## XmlTextReader::XmlTextReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) コンストラクタ

指定された文字列、XmlNodeType、[XmlParserContext](../../xmlparsercontext/) で、[XmlTextReader](../) クラスの新しいインスタンスを初期化します。

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| xmlFragment | const [String](../../../system/string/)\& | XML フラグメントを含む文字列。 |
| fragType | [XmlNodeType](../../xmlnodetype/) | XML フラグメントの XmlNodeType。フラグメント文字列が含められる内容も決定します。 |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | **xmlFragment** を解析する [XmlParserContext](../../xmlparsercontext/)。使用する [XmlNameTable](../../xmlnametable/)、エンコーディング、名前空間スコープ、現在の **xml:lang**、および **xml:space** スコープを含みます。 |

## XmlTextReader::XmlTextReader(const String\&) コンストラクタ

指定されたファイルで、[XmlTextReader](../) クラスの新しいインスタンスを初期化します。

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | XML データを含むファイルの URL。[XmlTextReader::get_BaseURI](../get_baseuri/) はこの値に設定されます。 |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<XmlNameTable\>\&) コンストラクタ

指定されたファイルと [XmlNameTable](../../xmlnametable/) で、[XmlTextReader](../) クラスの新しいインスタンスを初期化します。

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<XmlNameTable> &nt)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | XML データを読み込むファイルの URL。 |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | 使用する [XmlNameTable](../../xmlnametable/)。 |

## 参照

* 列挙型 [XmlNodeType](../../xmlnodetype/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Stream](../../../system.io/stream/)
* クラス [XmlTextReader](../)
* クラス [String](../../../system/string/)
* クラス [XmlNameTable](../../xmlnametable/)
* クラス [TextReader](../../../system.io/textreader/)
* クラス [XmlParserContext](../../xmlparsercontext/)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)