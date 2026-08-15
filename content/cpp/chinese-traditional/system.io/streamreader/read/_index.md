---
title: Read()
second_title: Aspose.Slides 的 C++ API 參考
description: 從串流讀取單一字元。
type: docs
weight: 40
url: /zh-hant/system.io/streamreader/read/
---
## StreamReader::Read() 方法


從串流讀取單一字元。

```cpp
virtual int System::IO::StreamReader::Read() override
```


### 返回值

以 UTF-16 編碼的讀取字元；如果該字元在 UTF-16 中以兩個碼點表示，則僅返回高位代理項。

## StreamReader::Read(ArrayPtr\<char_t\>, int, int) 方法


從串流讀取指定數量的字元，將其轉換為 UTF-16 編碼，並將產生的 UTF-16 字元寫入指定的字元陣列，從指定位置開始寫入。

```cpp
virtual int System::IO::StreamReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 用於寫入從串流讀取的字元之 UTF-16 字元陣列 |
| index | int | **buffer** 中以 0 為起點的索引，指示寫入起始位置 |
| count | int | 從串流讀取的字元數量 |

### 返回值

從串流讀取的字元數量

## 另見

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 類別 [StreamReader](../)
* 命名空間 [System::IO](../../)
* Library [Aspose.Slides](../../../)