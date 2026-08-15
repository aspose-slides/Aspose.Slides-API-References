---
title: Write()
second_title: Aspose.Slides for C++ API 參考文件
description: 如果包裝模式為二進位，則將指定位元組陣列的指定子範圍寫入串流；否則將指定位元組陣列的指定子範圍轉換為 char_type 類型，然後將結果寫入串流。
type: docs
weight: 79
url: /zh-hant/system.io/basicstdiostreamwrapper/write/
---
## BasicSTDIOStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 方法

如果包裝模式為二進位，則將指定位元組陣列的指定子範圍寫入串流；否則將指定位元組陣列的指定子範圍轉換為 char_type 類型，然後寫入結果至串流。

```cpp
virtual void System::IO::BasicSTDIOStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 包含要寫入之位元組的陣列 |
| offset | **int32_t** | **buffer** 中子範圍寫入開始位置的 0 為基礎索引 |
| count | **int32_t** | 子範圍中要寫入的元素數量 |

## BasicSTDIOStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 方法

將指定位元組陣列的指定子範圍寫入串流。

```cpp
virtual void System::IO::BasicSTDIOStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 包含要寫入之位元組的陣列視圖 |
| offset | **int32_t** | **buffer** 中子範圍寫入開始位置的 0 為基礎索引 |
| count | **int32_t** | 子範圍中要寫入的元素數量 |

## 另請參閱

* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 類別 [BasicSTDIOStreamWrapper](../)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)