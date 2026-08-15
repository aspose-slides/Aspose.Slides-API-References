---
title: Read()
second_title: Aspose.Slides for C++ API 參考文件
description: 從串流讀取指定數量的位元組，並將其寫入指定的位元組陣列。
type: docs
weight: 196
url: /zh-hant/system.net.sockets/networkstream/read/
---
## NetworkStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 方法


從串流讀取指定數量的位元組，並將其寫入指定的位元組陣列。

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 讀取的位元組將寫入的位元組陣列。 |
| offset | **int32_t** | 指定陣列中以位元組為單位的偏移量。 |
| size | **int32_t** | 要讀取的位元組數量。 |

### 返回值

已讀取的位元組數量。

## NetworkStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 方法


從串流讀取指定數量的位元組，並將其寫入指定的位元組陣列。

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 用於寫入讀取位元組的位元組陣列檢視 |
| offset | **int32_t** | 在 **buffer** 中以 0 為起點的寫入位置 |
| size | **int32_t** | 要讀取的位元組數量 |

### 返回值

已讀取的位元組數量

## 另見

* 類型別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [NetworkStream](../)
* 命名空間 [System::Net::Sockets](../../)
* 函式庫 [Aspose.Slides](../../../)