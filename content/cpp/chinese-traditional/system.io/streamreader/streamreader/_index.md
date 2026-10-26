---
title: StreamReader()
second_title: Aspose.Slides for C++ API 參考手冊
description: 建立 StreamReader 物件的實例，從指定的底層串流讀取字元，使用 UTF-8 編碼，且使用預設大小為 1024 位元組的緩衝區。
type: docs
weight: 1
url: /zh-hant/system.io/streamreader/streamreader/
---
## StreamReader::StreamReader(const SharedPtr\<Stream\>\&) 建構式

建立 [StreamReader](../) 物件的實例，從指定的底層串流讀取字元，使用 UTF-8 編碼，且使用預設大小為 1024 位元組的緩衝區。

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 用於讀取字元的底層串流 |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, bool) 建構式

建立 [StreamReader](../) 物件的實例，從指定的底層串流讀取字元，使用 UTF-8 編碼，且使用預設大小為 1024 位元組的緩衝區。一個參數指定是否應啟用位元順序標記 (BOM) 偵測。

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, bool detectEncodingFromByteOrderMarks)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 用於讀取字元的底層串流 |
| detectEncodingFromByteOrderMarks | **bool** | True to look for byte order marks at the beginning of the stream, otherwise - false |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&) 建構式

建立 [StreamReader](../) 物件的實例，從指定的底層串流讀取字元，使用指定的編碼，且使用預設大小為 1024 位元組的緩衝區。

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 用於讀取字元的底層串流 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 使用的編碼 |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool) 建構式

建立 [StreamReader](../) 物件的實例，從指定的底層串流讀取字元，使用指定的編碼，且使用預設大小為 1024 位元組的緩衝區。一個參數指定是否應啟用位元順序標記偵測。

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 用於讀取字元的底層串流 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 使用的編碼 |
| detectEncodingFromByteOrderMarks | **bool** | True to look for byte order marks at the beginning of the stream, otherwise - false |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool, int) 建構式

建立 [StreamReader](../) 物件的實例，從指定的底層串流讀取字元，使用指定的編碼，且使用指定大小的緩衝區。一個參數指定是否應啟用位元順序標記偵測。

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 用於讀取字元的底層串流 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 使用的編碼 |
| detectEncodingFromByteOrderMarks | **bool** | True to look for byte order marks at the beginning of the stream, otherwise - false |
| bufferSize | int | 緩衝區的最小大小（位元組） |

## StreamReader::StreamReader(const System::String\&) 建構式

建立 [StreamReader](../) 物件的實例，從指定的檔案讀取字元，使用 UTF-8 編碼，且使用預設大小為 4096 位元組的緩衝區。

```cpp
System::IO::StreamReader::StreamReader(const System::String &path)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | 要讀取字元的檔案路徑 |

## StreamReader::StreamReader(const System::String\&, bool) 建構式

建立 [StreamReader](../) 物件的實例，從指定的檔案讀取字元，使用 UTF-8 編碼，且使用預設大小為 4096 位元組的緩衝區。一個參數指定是否應啟用位元順序標記偵測。

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, bool detectEncodingFromByteOrderMarks)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | 要讀取字元的檔案路徑 |
| detectEncodingFromByteOrderMarks | **bool** | True to look for byte order marks at the beginning of the file, otherwise - false |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&) 建構式

建立 [StreamReader](../) 物件的實例，從指定的檔案讀取字元，使用指定的編碼，且使用預設大小為 4096 位元組的緩衝區。

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | 要讀取字元的檔案路徑 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 使用的編碼 |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool) 建構式

建立 [StreamReader](../) 物件的實例，從指定的檔案讀取字元，使用指定的編碼，且使用預設大小為 4096 位元組的緩衝區。一個參數指定是否應啟用位元順序標記偵測。

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | 要讀取字元的檔案路徑 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 使用的編碼 |
| detectEncodingFromByteOrderMarks | **bool** | True to look for byte order marks at the beginning of the file, otherwise - false |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool, int) 建構式

建立 [StreamReader](../) 物件的實例，從指定的檔案讀取字元，使用指定的編碼，且使用指定大小的緩衝區。一個參數指定是否應啟用位元順序標記偵測。

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | 要讀取字元的檔案路徑 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 使用的編碼 |
| detectEncodingFromByteOrderMarks | **bool** | True to look for byte order marks at the beginning of the file, otherwise - false |
| bufferSize | int | 緩衝區的最小大小（位元組） |

## 參見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 型別別名 [EncodingPtr](../../../system/encodingptr/)
* 類別 [Stream](../../stream/)
* 類別 [StreamReader](../)
* 類別 [String](../../../system/string/)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)