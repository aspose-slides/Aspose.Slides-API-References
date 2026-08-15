---
title: Read()
second_title: Aspose.Slides for C++ API 參考文件
description: 從串流中讀取指定數量的位元組，並寫入指定的位元組陣列。
type: docs
weight: 144
url: /zh-hant/system.io/unmanagedmemorystream/read/
---
## UnmanagedMemoryStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 方法


從流中讀取指定數量的位元組，並寫入指定的位元組陣列。

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 要寫入已讀取位元組的位元組陣列 |
| offset | **int32_t** | 在 **buffer** 中開始寫入的 0 起始位置 |
| count | **int32_t** | 要讀取的位元組數量 |

### 傳回值

已讀取的位元組數

## UnmanagedMemoryStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 方法


從流中讀取指定數量的位元組，並寫入指定的位元組陣列。

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 要寫入已讀取位元組的位元組陣列檢視 |
| offset | **int32_t** | 在 **buffer** 中開始寫入的 0 起始位置 |
| count | **int32_t** | 要讀取的位元組數量 |

### 傳回值

已讀取的位元組數

## 另請參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 類別 [UnmanagedMemoryStream](../)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)