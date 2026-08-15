---
title: Write()
second_title: Aspose.Slides for C++ API 參考文件
description: 將指定位元組陣列中的指定子範圍寫入至串流。
type: docs
weight: 209
url: /zh-hant/system.net.sockets/networkstream/write/
---
## NetworkStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 方法

將指定位元組陣列中的指定子範圍寫入至串流。

```cpp
void System::Net::Sockets::NetworkStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 包含要寫入之位元組的陣列。 |
| offset | **int32_t** | 指定陣列中以位元組計的偏移量。 |
| size | **int32_t** | 要寫入之子範圍的元素數量。 |

## NetworkStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 方法

將指定位元組陣列中的指定子範圍寫入至串流。

```cpp
void System::Net::Sockets::NetworkStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 包含要寫入之位元組的陣列視圖 |
| offset | **int32_t** | 在 **buffer** 中子範圍寫入開始位置的 0 基索引 |
| size | **int32_t** | 要寫入之子範圍的元素數量 |

## 另見

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)