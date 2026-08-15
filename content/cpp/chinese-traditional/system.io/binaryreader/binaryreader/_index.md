---
title: BinaryReader()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立 BinaryReader 類別的實例，使用 UTF-8 編碼從指定的資料流讀取資料。
type: docs
weight: 1
url: /zh-hant/system.io/binaryreader/binaryreader/
---
## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&) 建構函式


建立 [BinaryReader](../) 類別的實例，該類別使用 UTF-8 編碼從指定的資料流讀取資料。

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 輸入資料流 |

## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&) 建構函式


建立 [BinaryReader](../) 類別的實例，該類別使用指定的編碼從指定的資料流讀取資料。

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 輸入資料流 |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | 要使用的編碼 |

## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&, bool) 建構函式


建立 [BinaryReader](../) 類別的實例，該類別使用指定的編碼從指定的資料流讀取資料。

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding, bool leaveOpen)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 輸入資料流 |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | 要使用的編碼 |
| leaveOpen | **bool** | 指定在目前物件被釋放後，是否應保持資料流 **input** 開啟 (true) 或關閉 (false) |

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [Stream](../../stream/)
* 類別 [BinaryReader](../)
* 類別 [Encoding](../../../system.text/encoding/)
* 命名空間 [System::IO](../../)
* Library [Aspose.Slides](../../../)