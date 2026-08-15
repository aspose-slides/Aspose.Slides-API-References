---
title: Write()
second_title: Aspose.Slides C++ API 參考
description: 將指定位元組陣列的指定子區段寫入串流。
type: docs
weight: 248
url: /zh-hant/system.io/filestream/write/
---
## FileStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

將指定位元組陣列的指定子區段寫入串流。

```cpp
void System::IO::FileStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 包含要寫入之位元組的陣列。 |
| offset | **int32_t** | **buffer** 中開始寫入子區段的 0 基索引。 |
| count | **int32_t** | 要寫入之子區段的元素數量。 |

## FileStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method

將指定位元組陣列的指定子區段寫入串流。

```cpp
void System::IO::FileStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 包含要寫入之位元組的陣列檢視。 |
| offset | **int32_t** | **buffer** 中開始寫入子區段的 0 基索引。 |
| count | **int32_t** | 要寫入之子區段的元素數量。 |

## 另請參閱

* 型別別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [FileStream](../)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)