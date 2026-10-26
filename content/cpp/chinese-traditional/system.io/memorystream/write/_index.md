---
title: Write()
second_title: Aspose.Slides for C++ API 參考
description: 將指定位元組陣列中指定的子範圍寫入至資料流。
type: docs
weight: 92
url: /zh-hant/system.io/memorystream/write/
---
## MemoryStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 方法

將指定位元組陣列中指定的子範圍寫入至資料流。

```cpp
void System::IO::MemoryStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 包含要寫入之位元組的陣列 |
| offset | **int32_t** | 在 **buffer** 中子範圍寫入開始的位置，採用以 0 為起始的索引 |
| count | **int32_t** | 要寫入之子範圍的元素數量 |

## MemoryStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 方法

將指定位元組陣列中指定的子範圍寫入至資料流。

```cpp
void System::IO::MemoryStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 包含要寫入之位元組的陣列視圖 |
| offset | **int32_t** | 在 **buffer** 中子範圍寫入開始的位置，採用以 0 為起始的索引 |
| count | **int32_t** | 要寫入之子範圍的元素數量 |

## 另見

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 類別 [MemoryStream](../)
* 命名空間 [System::IO](../../)
* Library [Aspose.Slides](../../../)