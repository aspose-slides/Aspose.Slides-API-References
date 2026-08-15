---
title: Write()
second_title: Aspose.Slides for C++ API 參考
description: 將指定位元組陣列中的指定子範圍寫入底層串流。
type: docs
weight: 66
url: /zh-hant/system.io/bufferedstream/write/
---
## BufferedStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 方法

將指定位元組陣列中指定的子範圍寫入底層串流。

```cpp
virtual void System::IO::BufferedStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 包含要寫入的位元組的陣列 |
| offset | **int32_t** | 在 **buffer** 中以 0 為起始的索引，指出寫入子範圍的起始位置 |
| count | **int32_t** | 要寫入的子範圍中元素的數量 |

## BufferedStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 方法

將指定位元組陣列中指定的子範圍寫入底層串流。

```cpp
virtual void System::IO::BufferedStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 包含要寫入的位元組的陣列 |
| offset | **int32_t** | 在 **buffer** 中以 0 為起始的索引，指出寫入子範圍的起始位置 |
| count | **int32_t** | 要寫入的子範圍中元素的數量 |

## 參見

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 類別 [BufferedStream](../)
* 命名空間 [System::IO](../../)
* Library [Aspose.Slides](../../../)