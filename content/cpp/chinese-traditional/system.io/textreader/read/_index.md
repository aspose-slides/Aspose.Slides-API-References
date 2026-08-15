---
title: Read()
second_title: Aspose.Slides for C++ API 參考
description: 從串流中讀取單一字元。
type: docs
weight: 40
url: /zh-hant/system.io/textreader/read/
---
## TextReader::Read() 方法

從串流中讀取單一字元。

```cpp
virtual int System::IO::TextReader::Read()
```

### 返回值

讀取以 UTF-16 編碼的字元；如果讀取的字元在 UTF-16 編碼中由兩個碼位表示，則僅返回高位代理項。

## TextReader::Read(ArrayPtr\<char_t\>, int, int) 方法

從串流中讀取指定數量的字元，並寫入指定的字元陣列，從指定位置開始。

```cpp
virtual int System::IO::TextReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 用於寫入從串流中讀取的字元之 UTF-16 字元陣列 |
| index | int | 在 **buffer** 中以 0 為起點的索引，指定寫入開始的位置 |
| count | int | 從串流中讀取的字元數量 |

### 返回值

從串流中讀取的字元數量

## 另請參閱

* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 類別 [TextReader](../)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)