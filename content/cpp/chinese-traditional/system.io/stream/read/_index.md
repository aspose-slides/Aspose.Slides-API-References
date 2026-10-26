---
title: Read()
second_title: Aspose.Slides for C++ API 參考文件
description: 從流中讀取指定數量的位元組，並將其寫入指定的位元組陣列。
type: docs
weight: 27
url: /zh-hant/system.io/stream/read/
---
## Stream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 方法

從流中讀取指定數量的位元組，並將其寫入指定的位元組陣列。

```cpp
virtual int32_t System::IO::Stream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 寫入已讀位元組的位元組陣列 |
| offset | **int32_t** | 在 **buffer** 中以 0 為起點的寫入位置 |
| count | **int32_t** | 要讀取的位元組數量 |

### 回傳值

已讀取的位元組數量

## Stream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 方法

從流中讀取指定數量的位元組，並將其寫入指定的位元組陣列。

```cpp
virtual int32_t System::IO::Stream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 寫入已讀位元組的位元組陣列檢視 |
| offset | **int32_t** | 在 **buffer** 中以 0 為起點的寫入位置 |
| count | **int32_t** | 要讀取的位元組數量 |

### 回傳值

已讀取的位元組數量

## Stream::Read(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) 方法

從流中讀取指定數量的位元組，並將其寫入指定的位元組陣列。

```cpp
template<std::size_t> int32_t System::IO::Stream::Read(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```

### 模板參數

| Parameter | Description |
| --- | --- |
| N | 堆疊陣列的大小 |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<**uint8_t**, N\>\& | 寫入已讀位元組的位元組堆疊陣列 |
| offset | **int32_t** | 在 **buffer** 中以 0 為起點的寫入位置 |
| count | **int32_t** | 要讀取的位元組數量 |

### 回傳值

已讀取的位元組數量

## Stream::Read(const System::Span\<uint8_t\>\&) 方法

從流中讀取指定數量的位元組，並將其寫入指定的位元組跨度。

```cpp
virtual int32_t System::IO::Stream::Read(const System::Span<uint8_t> &buffer)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [System::Span](../../../system/span/)\<**uint8_t**\>\& | 寫入已讀位元組的位元組跨度 |

### 回傳值

已讀取的位元組數量

## 另請參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Stream](../)
* Class [Span](../../../system/span/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)