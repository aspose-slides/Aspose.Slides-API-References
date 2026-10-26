---
title: StreamReader()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された基底ストリームから文字を読み取り、UTF-8 エンコーディングとデフォルトサイズ 1024 バイトのバッファを使用する StreamReader オブジェクトのインスタンスを作成します。
type: docs
weight: 1
url: /ja/system.io/streamreader/streamreader/
---
## StreamReader::StreamReader(const SharedPtr\<Stream\>\&) コンストラクタ

[StreamReader](../) オブジェクトのインスタンスを作成します。このオブジェクトは、UTF-8 エンコーディングを使用し、デフォルトサイズ 1024 バイトのバッファで、指定された基底ストリームから文字を読み取ります。

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 文字を読み取る基底ストリーム |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, bool) コンストラクタ

[StreamReader](../) オブジェクトのインスタンスを作成します。このオブジェクトは、UTF-8 エンコーディングを使用し、デフォルトサイズ 1024 バイトのバッファで、指定された基底ストリームから文字を読み取ります。また、バイトオーダーマーク検出を有効にするかどうかを指定するパラメータがあります。

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, bool detectEncodingFromByteOrderMarks)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 文字を読み取る基底ストリーム |
| detectEncodingFromByteOrderMarks | **bool** | ストリームの先頭でバイトオーダーマークを検索する場合は true、そうでなければ false |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&) コンストラクタ

[StreamReader](../) オブジェクトのインスタンスを作成します。このオブジェクトは、指定されたエンコーディングを使用し、デフォルトサイズ 1024 バイトのバッファで、指定された基底ストリームから文字を読み取ります。

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 文字を読み取る基底ストリーム |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 使用するエンコーディング |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool) コンストラクタ

[StreamReader](../) オブジェクトのインスタンスを作成します。このオブジェクトは、指定されたエンコーディングを使用し、デフォルトサイズ 1024 バイトのバッファで、指定された基底ストリームから文字を読み取ります。また、バイトオーダーマーク検出を有効にするかどうかを指定するパラメータがあります。

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 文字を読み取る基底ストリーム |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 使用するエンコーディング |
| detectEncodingFromByteOrderMarks | **bool** | ストリームの先頭でバイトオーダーマークを検索する場合は true、そうでなければ false |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool, int) コンストラクタ

[StreamReader](../) オブジェクトのインスタンスを作成します。このオブジェクトは、指定されたエンコーディングを使用し、指定されたサイズのバッファで、指定された基底ストリームから文字を読み取ります。また、バイトオーダーマーク検出を有効にするかどうかを指定するパラメータがあります。

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 文字を読み取る基底ストリーム |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 使用するエンコーディング |
| detectEncodingFromByteOrderMarks | **bool** | ストリームの先頭でバイトオーダーマークを検索する場合は true、そうでなければ false |
| bufferSize | int | バッファの最小サイズ（バイト単位） |

## StreamReader::StreamReader(const System::String\&) コンストラクタ

[StreamReader](../) オブジェクトのインスタンスを作成します。このオブジェクトは、UTF-8 エンコーディングを使用し、デフォルトサイズ 4096 バイトのバッファで、指定されたファイルから文字を読み取ります。

```cpp
System::IO::StreamReader::StreamReader(const System::String &path)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | 文字を読み取るファイルのパス |

## StreamReader::StreamReader(const System::String\&, bool) コンストラクタ

[StreamReader](../) オブジェクトのインスタンスを作成します。このオブジェクトは、UTF-8 エンコーディングを使用し、デフォルトサイズ 4096 バイトのバッファで、指定されたファイルから文字を読み取ります。また、バイトオーダーマーク検出を有効にするかどうかを指定するパラメータがあります。

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, bool detectEncodingFromByteOrderMarks)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | 文字を読み取るファイルのパス |
| detectEncodingFromByteOrderMarks | **bool** | ファイルの先頭でバイトオーダーマークを検索する場合は true、そうでなければ false |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&) コンストラクタ

[StreamReader](../) オブジェクトのインスタンスを作成します。このオブジェクトは、指定されたエンコーディングを使用し、デフォルトサイズ 4096 バイトのバッファで、指定されたファイルから文字を読み取ります。

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | 文字を読み取るファイルのパス |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 使用するエンコーディング |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool) コンストラクタ

[StreamReader](../) オブジェクトのインスタンスを作成します。このオブジェクトは、指定されたエンコーディングを使用し、デフォルトサイズ 4096 バイトのバッファで、指定された基底ストリームから文字を読み取ります。また、バイトオーダーマーク検出を有効にするかどうかを指定するパラメータがあります。

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | 文字を読み取るファイルのパス |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 使用するエンコーディング |
| detectEncodingFromByteOrderMarks | **bool** | ファイルの先頭でバイトオーダーマークを検索する場合は true、そうでなければ false |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool, int) コンストラクタ

[StreamReader](../) オブジェクトのインスタンスを作成します。このオブジェクトは、指定されたエンコーディングを使用し、指定されたサイズのバッファで、指定されたファイルから文字を読み取ります。また、バイトオーダーマーク検出を有効にするかどうかを指定するパラメータがあります。

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | 文字を読み取るファイルのパス |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 使用するエンコーディング |
| detectEncodingFromByteOrderMarks | **bool** | ファイルの先頭でバイトオーダーマークを検索する場合は true、そうでなれば false |
| bufferSize | int | バッファの最小サイズ（バイト単位） |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* クラス [Stream](../../stream/)
* クラス [StreamReader](../)
* クラス [String](../../../system/string/)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)