---
title: Write()
second_title: Aspose.Slides for C++ API 參考
description: 將指定的位元組陣列中指定的子範圍寫入至串流。
type: docs
weight: 53
url: /zh-hant/system.io/stream/write/
---
## Stream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 方法

將指定的位元組陣列中指定的子範圍寫入至串流。

```cpp
virtual void System::IO::Stream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 包含要寫入之位元組的陣列 |
| offset | **int32_t** | 在 **buffer** 中子範圍開始寫入的元素之零基索引 |
| count | **int32_t** | 子範圍中要寫入的元素數量 |

## Stream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 方法

將指定的位元組陣列中指定的子範圍寫入至串流。

```cpp
virtual void System::IO::Stream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 包含要寫入之位元組的陣列視圖 |
| offset | **int32_t** | 在 **buffer** 中子範圍開始寫入的元素之零基索引 |
| count | **int32_t** | 子範圍中要寫入的元素數量 |

## Stream::Write(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) 方法

將指定的位元組陣列中指定的子範圍寫入至串流。

```cpp
template<std::size_t> void System::IO::Stream::Write(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| N | 堆疊陣列的大小 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<**uint8_t**, N\>\& | 包含要寫入之位元組的堆疊陣列 |
| offset | **int32_t** | 在 **buffer** 中子範圍開始寫入的元素之零基索引 |
| count | **int32_t** | 子範圍中要寫入的元素數量 |

## Stream::Write(const System::ReadOnlySpan\<uint8_t\>\&) 方法

將指定的位元組跨度中指定的子範圍寫入至串流。

```cpp
virtual void System::IO::Stream::Write(const System::ReadOnlySpan<uint8_t> &buffer)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const [System::ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | 要從中讀取已寫入位元組的位元組跨度 |

## 另請參閱

* 型別別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [Stream](../)
* 類別 [ReadOnlySpan](../../../system/readonlyspan/)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)