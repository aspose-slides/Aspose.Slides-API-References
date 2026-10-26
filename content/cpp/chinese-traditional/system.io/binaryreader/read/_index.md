---
title: Read()
second_title: Aspose.Slides for C++ API 參考
description: 從輸入串流中讀取單一字符。
type: docs
weight: 66
url: /zh-hant/system.io/binaryreader/read/
---
## BinaryReader::Read() 方法


從輸入串流中讀取單一字符。

```cpp
virtual int System::IO::BinaryReader::Read()
```


### 返回值

讀取以 UTF-16 編碼的字符；如果讀取的字符在 UTF-16 編碼中由兩個碼點表示，則只返回高位代理項。

## BinaryReader::Read(ArrayPtr\<uint8_t\>, int, int) 方法


從輸入串流中讀取指定數量的位元組，並將它們寫入指定的位元組陣列。

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<uint8_t> buffer, int index, int count)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要寫入讀取位元組的位元組陣列 |
| index | int | 在 **buffer** 中以 0 為起點的寫入位置 |
| count | int | 要讀取的位元組數量 |

### 返回值

已讀取的位元組數量

## BinaryReader::Read(ArrayPtr\<char_t\>, int, int) 方法


從輸入串流中讀取指定數量的字符，將它們轉換為 UTF-16 編碼，並將產生的 UTF-16 字符寫入指定字符陣列的指定位置。

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 用於寫入從輸入串流讀取的字符的 UTF-16 字符陣列 |
| index | int | 在 **buffer** 中以 0 為起點的寫入索引 |
| count | int | 要從串流中讀取的字符數量 |

### 返回值

從輸入串流中讀取的字符數量

## 另請參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BinaryReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)