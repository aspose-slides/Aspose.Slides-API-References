---
title: Read()
second_title: Aspose.Slides for C++ API 參考
description: 從串流中讀取指定數量的位元組，並寫入指定的位元組陣列。
type: docs
weight: 79
url: /zh-hant/system.io/memorystream/read/
---
## MemoryStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 方法

從串流中讀取指定數量的位元組，並寫入指定的位元組陣列。

```cpp
int32_t System::IO::MemoryStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 用於寫入已讀位元組的位元組陣列 |
| offset | **int32_t** | 在 **buffer** 中以 0 為起點的寫入位置 |
| count | **int32_t** | 要讀取的位元組數量 |

### 返回值

已讀取的位元組數量

## MemoryStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 方法

從串流中讀取指定數量的位元組，並寫入指定的位元組陣列。

```cpp
int32_t System::IO::MemoryStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 用於寫入已讀位元組的位元組視圖 |
| offset | **int32_t** | 在 **buffer** 中以 0 為起點的寫入位置 |
| count | **int32_t** | 要讀取的位元組數量 |

### 返回值

已讀取的位元組數量

## 另見

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [MemoryStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)