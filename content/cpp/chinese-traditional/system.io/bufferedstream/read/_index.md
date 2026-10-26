---
title: Read()
second_title: Aspose.Slides C++ API 參考
description: 從底層串流讀取指定數量的位元組，並寫入指定的位元組陣列。
type: docs
weight: 53
url: /zh-hant/system.io/bufferedstream/read/
---
## BufferedStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 方法

從底層串流讀取指定數量的位元組，並寫入指定的位元組陣列。

```cpp
virtual int32_t System::IO::BufferedStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 用於寫入讀取的位元組的位元組陣列 |
| offset | **int32_t** | 在 **buffer** 中的 0 基位置，作為寫入的起始點 |
| count | **int32_t** | 要讀取的位元組數 |

### 傳回值

讀取的位元組數

## BufferedStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 方法

從底層串流讀取指定數量的位元組，並寫入指定的位元組陣列。

```cpp
virtual int32_t System::IO::BufferedStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 用於寫入讀取的位元組的位元組陣列 |
| offset | **int32_t** | 在 **buffer** 中的 0 基位置，作為寫入的起始點 |
| count | **int32_t** | 要讀取的位元組數 |

### 傳回值

讀取的位元組數

## 另請參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BufferedStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)