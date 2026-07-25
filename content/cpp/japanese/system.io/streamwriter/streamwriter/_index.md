---
title: StreamWriter()
second_title: Aspose.Slides for C++ API リファレンス
description: UTF-8 エンコーディングとデフォルトサイズ 1024 バイトのバッファを使用して、指定された基礎ストリームに文字を書き込む StreamWriter オブジェクトのインスタンスを作成します。
type: docs
weight: 1
url: /ja/system.io/streamwriter/streamwriter/
---
## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&) コンストラクタ

[StreamWriter](../) オブジェクトのインスタンスを作成します。指定された基礎ストリームに文字を書き込み、UTF-8 エンコーディングとデフォルトサイズ 1024 バイトのバッファを使用します。

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 文字を書き込む基礎ストリーム |

## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&) コンストラクタ

[StreamWriter](../) オブジェクトのインスタンスを作成します。指定された基礎ストリームに文字を書き込み、指定されたエンコーディングとデフォルトサイズ 1024 バイトのバッファを使用します。

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 文字を書き込む基礎ストリーム |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 使用するエンコーディング |

## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&, int, bool) コンストラクタ

[StreamWriter](../) オブジェクトのインスタンスを作成します。指定された基礎ストリームに文字を書き込み、指定されたエンコーディングと指定されたサイズのバッファを使用します。パラメーターは、[StreamWriter](../) オブジェクトが破棄されるときに基礎ストリームを閉じるかどうかを指定します。

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, int buffer_size, bool leave_open=false)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 文字を書き込む基礎ストリーム |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 使用するエンコーディング |
| buffer_size | int | バッファの最小サイズ（バイト） |
| leave_open | **bool** | 現在の [StreamWriter](../) オブジェクトが破棄された後に基礎ストリームを開いたままにするかどうかを指定します |

## StreamWriter::StreamWriter(const String\&) コンストラクタ

[StreamWriter](../) オブジェクトのインスタンスを作成します。指定されたファイルに文字を書き込み、UTF-8 エンコーディングとデフォルトサイズ 1024 バイトのバッファを使用します。

```cpp
System::IO::StreamWriter::StreamWriter(const String &path)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 文字を書き込むファイルのパス |

## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&) コンストラクタ

[StreamWriter](../) オブジェクトのインスタンスを作成します。指定されたファイルに文字を書き込み、指定されたエンコーディングとデフォルトサイズ 1024 バイトのバッファを使用します。パラメーターはデータをファイルに追加するか上書きするかを指定します。

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked())
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 文字を書き込むファイルのパス |
| append | **bool** | データを指定されたファイルに追加するか (true)、あるいはファイルを上書きするか (false) を指定します |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 使用するエンコーディング |

## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&, int) コンストラクタ

[StreamWriter](../) オブジェクトのインスタンスを作成します。指定されたファイルに文字を書き込み、指定されたエンコーディングとバッファサイズを使用します。パラメーターはデータをファイルに追加するか上書きするかを指定します。

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding, int buffer_size)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 文字を書き込むファイルのパス |
| append | **bool** | データを指定されたファイルに追加するか (true)、あるいはファイルを上書きするか (false) を指定します |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 使用するエンコーディング |
| buffer_size | int | 使用するバッファのサイズ |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [Stream](../../stream/)
* Class [StreamWriter](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)