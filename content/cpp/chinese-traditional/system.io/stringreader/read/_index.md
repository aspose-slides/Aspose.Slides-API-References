---
title: Read()
second_title: Aspose.Slides for C++ API 參考
description: 從串流中讀取單一字元。
type: docs
weight: 40
url: /zh-hant/system.io/stringreader/read/
---
## StringReader::Read() 方法


從串流中讀取單一字元。

```cpp
virtual int System::IO::StringReader::Read() override
```


### 返回值

已讀取的字元，若未讀取到字元則返回 -1

## StringReader::Read(ArrayPtr\<char_t\>, int, int) 方法


從串流中讀取指定數量的字元至指定位置開始的字元陣列。

```cpp
virtual int System::IO::StringReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 用於寫入從串流中讀取的字元的字元陣列 |
| index | int | 在 **buffer** 中的 0 為基礎的索引，表示寫入的起始位置 |
| count | int | 從串流中要讀取的字元數 |

### 返回值

從串流中讀取的字元數

## 另見

* 類型別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [StringReader](../)
* 命名空間 [System::IO](../../)
* 程式庫 [Aspose.Slides](../../../)