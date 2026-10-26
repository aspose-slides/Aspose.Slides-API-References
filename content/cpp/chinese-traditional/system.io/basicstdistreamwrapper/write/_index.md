---
title: Write()
second_title: Aspose.Slides for C++ API 參考
description: 如果封裝模式為二進位，將指定位元組陣列的指定子範圍寫入串流；否則，將指定位元組陣列的指定子範圍轉換為 char_type 類型，然後將結果寫入串流。不支援!
type: docs
weight: 79
url: /zh-hant/system.io/basicstdistreamwrapper/write/
---
## BasicSTDIStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

如果封裝模式為二進位，將指定位元組陣列的指定子範圍寫入串流；否則，將指定位元組陣列的指定子範圍轉換為 char_type 型別，然後將結果寫入串流。不支援！

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 包含欲寫入位元組的陣列。 |
| offset | **int32_t** | 在 **buffer** 中子範圍開始寫入的 0 起始索引。 |
| count | **int32_t** | 子範圍中要寫入的元素數量。 |

## BasicSTDIStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method

將指定位元組陣列的指定子範圍寫入串流。

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 包含欲寫入位元組的陣列檢視。 |
| offset | **int32_t** | 在 **buffer** 中子範圍開始寫入的 0 起始索引。 |
| count | **int32_t** | 子範圍中要寫入的元素數量。 |

## 另見

* 類型別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [BasicSTDIStreamWrapper](../)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)