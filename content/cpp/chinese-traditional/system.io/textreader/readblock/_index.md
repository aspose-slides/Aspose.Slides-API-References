---
title: ReadBlock()
second_title: Aspose.Slides for C++ API 參考文件
description: 從目前的文字讀取器讀取指定的最大字元數，並將資料寫入緩衝區，從指定的索引開始。
type: docs
weight: 53
url: /zh-hant/system.io/textreader/readblock/
---
## TextReader::ReadBlock(ArrayPtr\<char_t\>, int, int) 方法

從目前的文字讀取器讀取指定的最大字元數，並將資料寫入緩衝區，從指定的索引開始。

```cpp
virtual int System::IO::TextReader::ReadBlock(ArrayPtr<char_t> buffer, int index, int count)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | **buffer** 用於寫入讀取資料的字元緩衝區 |
| index | int | 在 **buffer** 中開始寫入的 0 基索引 |
| count | int | 要讀取的最大字元數 |

### 回傳值

實際讀取的字元數

## 另請參閱

* 類型別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [TextReader](../)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)