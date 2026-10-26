---
title: StreamWriter()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立一個 StreamWriter 物件的實例，該物件使用 UTF-8 編碼並以預設 1024 位元組的緩衝區，將字元寫入指定的基礎串流。
type: docs
weight: 1
url: /zh-hant/system.io/streamwriter/streamwriter/
---
## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&) 建構函式


建立一個 [StreamWriter](../) 物件的實例，該物件使用 UTF-8 編碼並以預設 1024 位元組的緩衝區，將字元寫入指定的基礎串流。

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 要寫入字元的基礎串流 |

## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&) 建構函式


建立一個 [StreamWriter](../) 物件的實例，該物件使用指定的編碼並以預設 1024 位元組的緩衝區，將字元寫入指定的基礎串流。

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 要寫入字元的基礎串流 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 要使用的編碼 |

## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&, int, bool) 建構函式


建立一個 [StreamWriter](../) 物件的實例，該物件使用指定的編碼與指定大小的緩衝區，將字元寫入指定的基礎串流。參數指定在 [StreamWriter](../) 物件釋放時是否關閉基礎串流。

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, int buffer_size, bool leave_open=false)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 要寫入字元的基礎串流 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 要使用的編碼 |
| buffer_size | int | 緩衝區的最小大小（位元組） |
| leave_open | **bool** | 指定在目前的 [StreamWriter](../) 物件釋放後，基礎串流是否保持開啟 |

## StreamWriter::StreamWriter(const String\&) 建構函式


建立一個 [StreamWriter](../) 物件的實例，該物件使用 UTF-8 編碼並以預設 1024 位元組的緩衝區，將字元寫入指定的檔案。

```cpp
System::IO::StreamWriter::StreamWriter(const String &path)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 要寫入字元的檔案路徑 |

## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&) 建構函式


建立一個 [StreamWriter](../) 物件的實例，該物件使用指定的編碼並以預設 1024 位元組的緩衝區，將字元寫入指定的檔案。參數指定是將資料附加至檔案還是覆寫檔案。

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked())
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 要寫入字元的檔案路徑 |
| append | **bool** | 指定資料是附加至指定檔案 (true) 還是覆寫檔案 (false) |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 要使用的編碼 |

## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&, int) 建構函式


建立一個 [StreamWriter](../) 物件的實例，該物件使用指定的編碼與緩衝區大小，將字元寫入指定的檔案。參數指定是將資料附加至檔案還是覆寫檔案。

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding, int buffer_size)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 要寫入字元的檔案路徑 |
| append | **bool** | 指定資料是附加至指定檔案 (true) 還是覆寫檔案 (false) |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 要使用的編碼 |
| buffer_size | int | 要使用的緩衝區大小 |

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 型別別名 [EncodingPtr](../../../system/encodingptr/)
* 類別 [Stream](../../stream/)
* 類別 [StreamWriter](../)
* 類別 [String](../../../system/string/)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)