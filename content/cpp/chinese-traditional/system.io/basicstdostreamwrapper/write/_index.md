---
title: Write()
second_title: Aspose.Slides for C++ API 參考
description: 如果 wrapping mode 為 binary，則將指定位元組陣列的指定子範圍寫入串流；否則將指定位元組陣列的指定子範圍轉換為 char_type 類型，然後將結果寫入串流。
type: docs
weight: 79
url: /zh-hant/system.io/basicstdostreamwrapper/write/
---
## BasicSTDOStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 方法


如果 wrapping mode 為 binary，則將指定位元組陣列的指定子區段寫入串流；否則將指定位元組陣列的指定子區段轉換為 char_type 類型，然後將結果寫入串流。

```cpp
virtual void System::IO::BasicSTDOStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 包含要寫入之位元組的陣列 |
| offset | **int32_t** | 在 **buffer** 中子區段開始寫入的 0 基索引 |
| count | **int32_t** | 要寫入之子區段的元素數量 |

## BasicSTDOStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 方法


將指定位元組陣列的指定子區段寫入串流。

```cpp
virtual void System::IO::BasicSTDOStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 包含要寫入之位元組的陣列檢視 |
| offset | **int32_t** | 在 **buffer** 中子區段開始寫入的 0 基索引 |
| count | **int32_t** | 要寫入之子區段的元素數量 |

## 參考

* 型別別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [BasicSTDOStreamWrapper](../)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)